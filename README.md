# Crowd OS: Autonomous Crowd Safety Grid
**Principal Architect:** Prasurjya Deka
**Contact:** prasurjyadeka130@gmail.com

## 1. Project Abstract
Crowd OS is a privacy-safe crowd management system created by Prasurjya Deka. It prevents stampedes using a novel "Aggregate & Compare" logic where **Stationary Thermal Sensors** (on poles) detect panic velocity, and **Wearable Wristbands** provide haptic guidance.

## 2. Technical Claims & Novelty (Prior Art)
To establish authenticity and non-infringement, Prasurjya Deka claims the following unique system architecture:

### A. Infrastructure-Based Sensing (The "Privacy-Safe Eye")
**Distinction from US Patent 12392583B2:**
Existing patents, such as US 12392583B2, describe "visual sensors integrated into tactical gear" worn by a user to detect personal threats .
**Crowd OS is different:**
*   **Stationary Deployment:** We use **Thermal Omni-Nodes** clamped to static infrastructure (walls/poles), NOT worn on the body.
*   **Fluid Dynamics Logic:** We use the **Watershed Algorithm** to detect "High Density" flow patterns of the *entire* crowd, rather than individual threats to a single wearer.

### B. The "SecureEvent" Dual-Trigger
An evacuation alarm is triggered ONLY when two independent variables match:
1.  **Infrastructure:** Thermal Node detects "High Velocity" (Panic Running).
2.  **Wearable:** Guardian Wristband detects "High Heart Rate" (Physiological Distress).

## 3. Hardware Stack & Attribution
*   **Wearable:** The "Guardian Band" is built upon the open-source **PhysioKit** architecture (Joshi et al., UCL) [License: CC BY 4.0].
*   **Sensor:** AMG8833 Infrared Array (Stationary).
*   **Network:** DeepLight-RPL Mesh Protocol (Independent of 4G/5G).

## 4. Commercial Inquiries & Verification
This repository serves as a **Defensive Publication** to establish Prior Art for Prasurjya Deka.
For licensing inquiries or verification of ownership, please contact:

**Prasurjya Deka**
📧 **Email:** prasurjyadeka130@gmail.com
