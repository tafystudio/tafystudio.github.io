---
title: Roadmap
layout: default
permalink: /roadmap/
---

# Roadmap

**Now (Phase 1):** 30-minute first motion
- One-line install, Hub UI, Node-RED
- ESP32 web flasher (diff-drive + ToF)
- Auto-discover devices, starter flows

**Next (Phase 1.5):**
- NATS JetStream **KV** device registry (watchers + TTL)
- Snapshots/restore

**Phase 2:** HAL + driver breadth + prebuilt images
- HAL v1 (motor/servo/imu/range/camera)
- Driver containers (PWM/ESC, IMU, ToF, USB cam)
- Prebuilt Pi/Jetson images; health & logs

**Phase 3:** Vision + scaling + sim
- GPU scheduling; CPU/GPU vision containers
- Rolling updates; 2D sim with HAL parity

**Phase 4+:** Security hardening, cloud-optional, functions, ROS 2 bridge, manipulation groundwork
