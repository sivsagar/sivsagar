<h1 align="center">Siv Sagar</h1>
<p align="center">
  <b>Embedded Systems | UAV Flight Firmware | Wearable Health Tech | Edge AI</b><br/>
  B.Tech CSE (3rd year) at Adamas University, Kolkata
</p>

<p align="center">
  <a href="https://linkedin.com/in/siv-sagar-114b6a2a9"><img src="https://img.shields.io/badge/LinkedIn-Siv_Sagar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:sivsagar29112006@gmail.com"><img src="https://img.shields.io/badge/Email-sivsagar29112006@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/AyuScan"><img src="https://img.shields.io/badge/Team-AyuScan-181717?style=for-the-badge&logo=github&logoColor=white" alt="AyuScan GitHub organization"/></a>
</p>

---

## About

I build hardware and software that work together: flight firmware, sensor-driven wearables and real-time vision on small devices. I am a DGCA-certified drone pilot and the Student Coordinator of the Adamas Robotics & AI Club, where I run UAV and robotics workshops for junior students.

- Porting the ArduCopter flight stack to an indigenous RISC-V board for NIDAR 2026-27 (Team PROJECT DELI)
- Built AyuScan, a wearable patient-monitoring system, and its camera-based extension, AyuScan Contactless
- Completed an embedded firmware internship at C-DAC CINE, IIT Guwahati
- Looking for research and engineering internships in UAV systems, embedded firmware, edge AI and health tech

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| **VEGAPilot** | ArduCopter flight stack ported to the C-DAC ARIES v3 board (THEJAS32 / VEGA ET1031, RV32IM, no hardware FPU, 256 KB RAM). Replaced the heavy EKF with DCM attitude estimation and a lightweight altitude complementary filter, re-scheduled the main loop to 100 Hz, and built the Linux HAL for the IMU, barometer, compass, ELRS receiver and PWM outputs. Tested in SITL. | C++, Embedded Linux, RISC-V, ArduPilot |
| **AyuScan + ReHAP** | Low-cost wrist-worn patient monitor (ECG, heart rate, SpO2, temperature, motion) streaming over BLE to a Raspberry Pi hub with a multi-patient dashboard and three on-hub AI models. ReHAP is a behind-the-ear haptic alert that warns patients without a screen or alarm. | ESP32-C6, BLE, PyTorch, XGBoost, React |
| **AyuScan Contactless** | Offline, camera-based vital sign and fall detection. MediaPipe landmarks feed PyTorch models for stress and fall detection, shown on a live dashboard. No video is stored or sent. | Raspberry Pi 5, MediaPipe, PyTorch, Flask, React |
| **Hydrocheck** | Wrist-worn dehydration and heat-stress wearable fusing GSR, PPG and IR temperature sensing, with an on-device TinyML risk classifier and BLE telemetry to a mobile app. | ESP32, TinyML, BLE, React/Capacitor |
| **AI-Powered Surveillance Drone** | Multi-sensor drone with YOLO detection (85%+ accuracy), GPS/IMU waypoint navigation (2 m or better path accuracy), 5 km+ telemetry and LiDAR obstacle avoidance. | Pixhawk, Raspberry Pi 5, YOLO, Python/C++ |
| **RC Bomb Detection Car** | Remote-controlled hazard-detection vehicle with 720p ESP32-CAM streaming, GPS tracking and GSM communication. | ESP32-CAM, GPS, GSM |

Code for the AyuScan projects lives in the [AyuScan organization](https://github.com/AyuScan).

## Experience

- **Embedded IoT Intern, C-DAC CINE, IIT Guwahati** (Jul to Aug 2026): firmware and LVGL touchscreen interfaces for a radiation survey meter on ESP32 and STM32, including Wi-Fi provisioning, live sensor display, configurable thresholds and SD card logging, validated on target hardware.
- **Student Coordinator, Adamas Robotics & AI Club** (May 2026 to present): lead club operations and run UAV and robotics workshops, covering ArduPilot/PX4, flight controller tuning and drone assembly.

## Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=py,c,cpp,java,js,bash,html,css,react,flask,pytorch,tensorflow,opencv,raspberrypi,arduino,linux,git,github" alt="Tech stack icons"/>
</p>

| Area | Tools |
|---|---|
| **Languages** | Python, C, C++, Embedded C, Java, Bash, JavaScript, HTML5, CSS |
| **UAV and flight control** | ArduPilot/ArduCopter (porting, HAL, scheduler), PX4, Betaflight, MAVLink, Mission Planner, QGroundControl, SITL, PID tuning |
| **Hardware** | RISC-V (RV32IM, THEJAS32, ARIES v3), ESP32, STM32, Raspberry Pi 5, Pixhawk, Arduino, BLE, RTOS, UART/I2C/SPI/CAN, PWM |
| **Controls and estimation** | Complementary filter, DCM, Kalman filter/EKF, biquad filters, sensor fusion |
| **AI/ML and vision** | YOLO, TinyML, TensorFlow Lite, PyTorch, XGBoost, OpenCV, MediaPipe, edge inference |
| **Tools and design** | Flask, React, Git, Waf, GCC cross-toolchains, EasyEDA, Fusion 360, SolidWorks, 3D printing (PLA/PETG/TPU) |

## Highlights

- Grand Winner (Healthcare Sector), Project Morpheus 2026, SIT Lonavala
- 1st Prize, National Workshop on Innovative & Sustainable Technologies, IIC Jadavpur University
- 9th Position, Tech Expo 2026, IIT Guwahati
- 1st Position in Robo Soccer and Line Follower (Signifiya 2026) and Robo Terrain (Signifiya 2025)
- Participant, CodeBot Hackathon, ARTPARK IISc Bangalore and TIH IIT Bombay
- DGCA Certified Drone Pilot (Small Category)

## Get in touch

I am open to research internships and collaborations in UAV systems, embedded firmware, edge AI and wearable health tech. The best way to reach me is by [email](mailto:sivsagar29112006@gmail.com) or [LinkedIn](https://linkedin.com/in/siv-sagar-114b6a2a9).
