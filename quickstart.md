---
title: Quickstart — Install & first motion
layout: default
permalink: /quickstart/
---

# Quickstart

**Goal:** from blank device to a moving robot in ≤30 minutes.

## 1) Install the DROS on your host board

```bash
curl -fsSL get.tafy.sh | bash
```

* This installs k3s, the Tafy Hub, Node-RED, and NATS.

* When finished, open https://tafy.local on your laptop (same network).


## 2) Flash your ESP32 motor + sensor controller

1. In the Hub, open Devices → Flash.

1. Connect an ESP32-S3 (or classic ESP32) via USB.

1. Click Flash “Diff-Drive + ToF”. The browser uses Web Serial to install firmware.

1. Power the ESP32 from your robot controller; it will auto-discover in the Hub.

> Prefer USB-C native? Use an ESP32-S3 board.


## 3) Wire the starter kit

* Motors → motor driver (e.g., L298N/BTS7960) → ESP32 PWM pins

* ToF sensor (VL53L0X/HC-SR04) → ESP32 I²C/GPIO

* Pi/Jetson camera (optional) via USB or CSI


## 4) Import the “Avoid Obstacle” flow

1. Hub → Flows → Import “Avoid Obstacle”.

1. Click Deploy.

1. Your robot should move and avoid obstacles.


Next steps: try Teleop (gamepad/web joystick), or Follow Color (USB camera required).


> Stuck? See Docs → Troubleshooting or ask in Community.