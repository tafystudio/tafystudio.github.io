---
title: Drivers
---

# Drivers

- **Motor:** PWM/ESC
- **Sensors:** IMU (MPU6050), Range (VL53L0X/HC-SR04)
- **Camera:** USB/CSI via libcamera

Drivers speak a uniform **HAL** (topics & schemas). If hardware doesn’t match, the UI suggests a compatible driver or switches to a generic mode.
