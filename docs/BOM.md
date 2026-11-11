# Parts list and cost estimate

Rough estimate for **one prototype**, in Indian rupees. Rows marked *checked* were looked up online in November 2026; every other row is an estimate and must be confirmed with a supplier quote before buying.

| Group | Item | Qty | Low | High | Basis |
|---|---|---|---|---|---|
| Compute and sensing | NVIDIA Jetson Orin Nano Super developer kit (8 GB) | 1 | 35,000 | 55,000 | checked online Nov 2026 |
| Compute and sensing | NVMe SSD 256 GB | 1 | 2,500 | 2,500 | estimate |
| Compute and sensing | Depth camera (Luxonis OAK-D Lite or similar) | 1 | 15,000 | 32,000 | checked online Nov 2026 |
| Compute and sensing | 2D LiDAR (Slamtec RPLIDAR C1) | 1 | 7,000 | 9,500 | checked online Nov 2026 |
| Compute and sensing | GPS module (u-blox NEO-M8N class) | 1 | 2,500 | 2,500 | estimate |
| Compute and sensing | IMU (BNO055 / BNO085) | 1 | 2,500 | 2,500 | estimate |
| Compute and sensing | ESP32 dev board | 1 | 600 | 600 | estimate |
| Compute and sensing | Waterproof ultrasonic sensor (JSN-SR04T) | 3 | 1,200 | 1,200 | estimate |
| Compute and sensing | 4G USB modem | 1 | 2,500 | 2,500 | estimate |
| Drive | 24 V geared DC motor with encoder | 4 | 24,000 | 24,000 | estimate |
| Drive | Dual-channel 30 A motor driver | 2 | 14,000 | 14,000 | estimate |
| Drive | Pneumatic wheel with hub (10-12 inch) | 4 | 8,000 | 8,000 | estimate |
| Drive | Frame: aluminium extrusion, sheet metal, fasteners | 1 | 20,000 | 20,000 | estimate |
| Arm | 5-axis arm: joint actuators, links, bearings | 1 | 50,000 | 50,000 | estimate |
| Arm | Gripper with servo and soft pads | 1 | 4,000 | 4,000 | estimate |
| Arm | Servo / actuator controller | 1 | 2,000 | 2,000 | estimate |
| Power | 24 V 20 Ah LiFePO4 battery with BMS | 1 | 18,000 | 18,000 | estimate |
| Power | Battery charger | 1 | 3,000 | 3,000 | estimate |
| Power | DC-DC converters (24-12 V and 24-5 V) | 2 | 2,000 | 2,000 | estimate |
| Power | Fuse, contactor, E-stop, wiring, connectors | 1 | 5,000 | 5,000 | estimate |
| Body | Hopper sheet metal and 12 V linear actuator | 1 | 5,000 | 5,000 | estimate |
| Body | Beacon, lights, sealed electronics box, cable glands | 1 | 5,000 | 5,000 | estimate |
| | **Subtotal** | | **228,800** | **268,300** | |
| | **With 10% spare margin** | | **251,680** | **295,130** | |

Not included: workshop or machine-time fees, shipping, GST differences between sellers, and your own time.

## Prices that were checked

- Jetson Orin Nano Super developer kit: listings range from about Rs 30,000 on IndiaMART to Rs 54,999 at ThinkRobotics. [IndiaMART](https://m.indiamart.com/proddetail/nvidia-jetson-nano-developer-kit-2853204275991.html), [ThinkRobotics](https://thinkrobotics.com/ar/products/nvidia-jetson-orin-nano-developer-kit)
- RPLIDAR C1: Rs 6,749 at Robu, Rs 9,350 at ThinkRobotics. [Robu](https://stg.robu.in/?p=1840849), [ThinkRobotics](https://thinkrobotics.com/ar/products/slamtec-rplidar-c1-laser-ranging-sensor)
- OAK-D Lite: Rs 31,650 at ThinkRobotics; one Indian review quotes Rs 12,000-15,000. [ThinkRobotics](https://thinkrobotics.com/ar/products/oak-d-lite-opencv-ai-machine-vision-kit-online), [Zbotic](https://zbotic.in/oak-d-lite-ai-camera-depth-ai-on-edge-device-review/)

## Biggest cost risk: the arm

The arm reaches about 0.8 m. Holding a 0.5 kg item at that reach, plus the arm's own weight, needs roughly 12 N·m (about 120 kg·cm) at the shoulder. Hobby servos are borderline at that load, so the shoulder and elbow probably need geared stepper or brushless joint actuators. The Rs 50,000 arm line assumes a custom arm built in a workshop; a bought 5-axis arm of this reach will cost more.
