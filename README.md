# Crowd OS: Autonomous Crowd Safety Grid
**Principal Architect & Creator:** Prasurjya Deka

## 1. Project Abstract
Crowd OS is a privacy-safe crowd management system created by Prasurjya Deka. It utilizes a novel "Aggregate & Compare" logic where stationary thermal sensors detect crowd velocity, and wearable devices provide haptic guidance.

## 2. Technical Claims by Prasurjya Deka
To establish authenticity and Prior Art, Prasurjya Deka claims the following unique system logic:

### A. The "Privacy-Safe Eye" (Infrastructure-Based Sensing)
*   **Innovation:** Unlike existing "Body Worn Safety Devices" (e.g., US Patent 12392583B2) which place cameras on tactical gear , the system designed by Prasurjya Deka uses **Stationary Thermal Omni-Nodes** (AMG8833 Sensors) clamped to poles .
*   **Logic:** The system detects "High Density" patterns using a custom implementation of the **Watershed Algorithm**, separating merged heat blobs into headcounts .

### B. The "SecureEvent" Dual-Trigger Logic
The evacuation protocol designed by Prasurjya Deka activates ONLY when two independent variables are confirmed:
1.  **Variable A (Infrastructure):** Thermal Node detects "High Velocity" (Panic Running).
2.  **Variable B (Wearable):** Guardian Wristband detects "High Heart Rate" (Distress Signal).

## 3. Hardware Architecture
*   **Wristband Design:** The "Guardian Band" utilizes the RP2040 microcontroller and PPG sensors. This hardware integration was designed by Prasurjya Deka based on the open-source **PhysioKit** framework .
*   **Network Topology:** The system uses the **DeepLight-RPL** protocol to create a "Bucket Brigade" mesh network, ensuring connectivity without 4G/5G .

## 4. Contact & Verification
For commercial inquiries regarding the Crowd OS architecture, contact the creator:
**Prasurjya Deka**
prasurjyadeka130@gmail.com
