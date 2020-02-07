
```
# *** THINGS TO CHANGE/CHECK: ***
# mcu paths                             [mcu] section
# Thermistor types                      [extruder] and [heater_bed] sections - See 'sensor types' list at end of file
# FSR switch (z endstop) location       [homing_override] section
# FSR switch (z endstop) offset for Z0  [stepper_z] section
# Probe points                          [quad_gantry_level] section
# Min & Max gantry corner postions      [quad_gantry_level] section
# PID tune                              [extruder] and [heater_bed] sections
# Fine tune E steps                     [extruder] section

# Sensor Types
#   "EPCOS 100K B57560G104F"
#   "ATC Semitec 104GT-2"
#   "NTC 100K beta 3950"
#   "Honeywell 100K 135-104LAG-J01"
#   "NTC 100K MGB18-104F39050L32" (Keenovo Heater Pad)
#   "AD595"
#   "PT100 INA826"
#   "beta4200" aka TL 300c blue wire thermistor

# TriangleLab Beta3950k Thermistor Definition
# Use this thermistore type for the TL blue cabled thermistor.
#[thermistor beta4200]
#temperature1: 25.0 
#resistance1: 100000.0 
#beta: 4200

# ========================== Pin Definitions ==========================
# X_STEP_PIN         2.2
# X_DIR_PIN          2.6
# X_ENABLE_PIN       2.1
# X_MIN_PIN          1.29
# X_MAX_PIN          1.28
# X_UART_RX          1.17
# X_UART_TX          4.29

# Y_STEP_PIN         0.19
# Y_DIR_PIN          0.20
# Y_ENABLE_PIN       2.8
# Y_MIN_PIN          1.27
# Y_MAX_PIN          1.26
# Y_UART_RX          1.15
# Y_UART_TX          1.16

# Z_STEP_PIN         0.22
# Z_DIR_PIN          2.11
# Z_ENABLE_PIN       0.21
# Z_MIN_PIN          1.25
# Z_MAX_PIN          1.24
# Z_UART_RX          1.10
# Z_UART_TX          1.14

# E0_STEP_PIN        2.13
# E0_DIR_PIN         0.11
# E0_ENABLE_PIN      2.12
# E0_UART_RX         1.8
# E0_UART_TX         1.9

# E1_STEP_PIN        0.1
# E1_DIR_PIN         0.0
# E1_ENABLE_PIN      0.10
# E1_UART_RX         1.1
# E1_UART_TX         1.4

# HE1                2.4
# HE0                2.7
# BED                2.5
# TH1 (H1 Temp)      0.25
# TH0 (H0 Temp)      0.24
# TB  (Bed Temp)     0.23
# FAN                2.3
# SERVO              2.0
# =====================================================================
```