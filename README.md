# Edge-Deployed Air Safety Assistant

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

AetherIO is a vision-augmented occupational safety prototype for labs, soldering stations, and small industrial workspaces. The core idea is simple: do not wait for air quality to become dangerous when visual activity can predict the risk earlier.

## Concept

- Raspberry Pi 5 as the local edge server
- USB camera for workspace activity detection
- ESP32 or simulated sensor input for VOC and air quality signals
- Direct Ethernet operation for low-latency, offline demos
- Dark operator dashboard for hazards, sensor trends, and safety state

## Current Repository Contents

```text
template/          # static dashboard screens
plan.txt           # project plan and demo pitch
workdonetillnow.md # build summary and presentation notes
```

## Demo Story

```text
camera sees activity -> local decision engine -> air risk state rises -> dashboard flags hazard -> ventilation state changes
```

## Status

This repository is a presentation-ready prototype package. It currently emphasizes dashboard design, system architecture, and demo narrative rather than production firmware.

## Next Build Step

Convert the static dashboard package into a runnable Raspberry Pi service with FastAPI, WebSockets, OpenCV motion detection, and real or simulated ESP32 sensor input.
