# 🤖 Project OmniCore: Universal Modular AMR Platform & OmniLift

**Smart India Hackathon 2026**
* **Team Name:** Astra APCOER
* **Team ID:** 188951
* **Problem Statement ID:** 26112
* **Theme:** Robotics and Drones (Hardware)

---

## 📌 Overview
Warehouse Autonomous Mobile Robots (AMRs) are typically single-purpose and costly (US$10k–100k each). Every new task requires a different robot, causing fleets to sit idle. 

**Project OmniCore** solves this by introducing an additive-optimised AMR base that supports tool-less swappable modules. Featuring a kinematic Quick-Lock system, it automatically docks power, data, and E-stop connections in under 2 minutes, bringing down costs and boosting warehouse adaptability.

## 🚀 Key Features
* **Generative-Design Platform (Part A):** 30–40% lighter chassis with a 3-ball kinematic Quick-Lock coupling, swappable drive pods, and side-slide battery swapping. Plug-and-play module ID automatically loads the required control profile.
* **OmniLift Bin-Handling (Part B):** A dedicated attachment featuring a twin mast and lead-screw lift. It elevates 600x400 KLT bins (≤ 30 kg) to 1.2 m rack levels, with telescopic arms reaching 400 mm beyond the footprint.
* **Cost Efficient:** Estimated base BOM is ~₹6.5 lakh (~US$7.6k), significantly lower than standard commercial AMRs.
* **Make in India:** Additive Manufacturing (AM) nodes and replacement spares can be 3D printed locally, supporting the National Strategy on Additive Manufacturing.

## 🛠️ System Architecture & Specs

### Hardware Stack
* **Drive System:** Differential drive with 2x 400 W BLDC hub pods and 4 sprung casters (Speed: up to 1.5 m/s).
* **Power:** 48 V 40 Ah LiFePO4 battery (1.92 kWh) providing ~7.5 hours per shift.
* **Safety:** ISO 3691-4 compliant. Speed caps at 0.5 m/s when mast > 0.6 m. Physical bumper and LiDAR fields actively trigger the E-stop chain.

### Software & Perception Stack
* **Compute:** Jetson Orin Nano
* **Navigation:** ROS 2 Nav2 SLAM with AprilTag precision docking (±5 mm).
* **Sensors:** 2x 360° LiDAR on diagonal corners + Front & Rear depth cameras.
* **Fleet Interface:** VDA 5050 protocol for WMS/Fleet management integration.

## 💰 Bill of Materials (BOM) Estimate

| Component | Cost (₹ '000) |
| :--- | :--- |
| Sensors (LiDAR + cams) | 290 |
| Electronics & assembly | 100 |
| Drive pods + casters | 105 |
| Chassis (extrusion + AM) | 70 |
| Battery 48 V LiFePO4 | 60 |
| Compute (Orin Nano) | 25 |
| **Total Base BOM** | **~650** |

## 🔗 Important Links
* **YouTube Demo Video:** [Link to your video here]
* **Fusion 3D Model:** [Link to your 3D model here]

---
*Built with ❤️ by Team Astra APCOER for SIH 2026*
