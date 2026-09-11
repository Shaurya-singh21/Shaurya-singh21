<div align="center">

# Hi, I'm Shaurya Singh 👋
### Embedded Firmware & Edge AI Engineer

Bare-metal ARM Cortex-M4 firmware and on-device inference — bridging raw silicon and edge intelligence.

[LinkedIn](https://linkedin.com/in/shaurya-singh-16270b336) · [Email](mailto:shauryasingh.uno@gmail.com) · [GitHub](https://github.com/Shaurya-singh21)

</div>

---

## 🔭 Current Focus
- Working on SIH Problem Statement 26058 - **Development of a Low-Power, Real-Time Adaptive Software-Defined Sonar Transmitter Payload for Autonomous Underwater Vehicles (AUVs)**
- Deepening FreeRTOS internals — synchronization primitives, ISR/DMA integration
- Working through CUDA fundamentals (naive → tiled shared-memory → cuBLAS) ahead of TensorRT deployment
- Open to embedded firmware / edge AI internships

## 🛠️ Featured Projects

### Custom UART Bootloader + IAP Firmware Update
Dual-partition bare-metal bootloader on STM32F446RE with CRC32 boot validation via the hardware CRC peripheral, selective sector erase, and a Python/pyserial host tool that streams firmware in checksummed 256-byte chunks over UART.
- **Stack:** STM32F446RE (zero-HAL, register-level), C, Python
- **Status:** Complete — full erase/transfer/flash/jump cycle verified end-to-end)
- **Code:** https://github.com/Shaurya-singh21/Custom_IAP_Bootloader
  
### FreeRTOS Motor Bearing Fault Detection
Real-time fault classification (healthy / imbalance / bearing fault / transient shock) on a spinning motor. MPU6050 accelerometer sampled via I2C+DMA double-buffering, on-device FFT feature extraction, Random Forest inference (15 features, 4 classes) running inside a multi-task FreeRTOS pipeline, results out over UART and OLED.
- **Stack:** STM32F446RE, FreeRTOS, C, scikit-learn (offline training)
- **Status:** Complete — inference pipeline running on-device with OLED integartion complete
- **Code:** https://github.com/Shaurya-singh21/TinyML-Motor-Fault-Detection-Predictive-Maintenance
  
### DMA-Driven Environmental Monitoring Platform
Nine-peripheral, zero-HAL bare-metal platform: dual DMA channels, ADC, four timers, I2C, UART, GPIO/EXTI, and an SSD1306 OLED. Closed-loop actuation — vents and a fan driven directly off temperature thresholds.
- **Stack:** STM32F446RE (register-level, no HAL)
- **Status:** Complete
- **Code:** https://github.com/Shaurya-singh21/DMA-Driven-Environmental-Monitoring-Control-Platform

### Neuromorphic FPGA SNN Accelerator — ISRO URSC Research Internship
Six-stage pipelined spiking neural network accelerator on a Xilinx Virtex-7, evaluated against a CNN baseline: 95.0% accuracy, 7x fewer parameters, 39% lower energy.
- **Stack:** Verilog RTL, Xilinx Virtex-7
- **Status:** Complete (internship deliverable)
- **Code:** https://github.com/Shaurya-singh21/URSC_Internship_2026

## 💻 Tech Stack

<table>
  <tr>
    <td align="left" valign="middle"><b>Embedded / Systems</b></td>
    <td valign="middle">
      <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
      <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
      <img src="https://img.shields.io/badge/ARM%20Cortex--M-0091BD?style=for-the-badge&logo=arm&logoColor=white" />
      <img src="https://img.shields.io/badge/Verilog-245464?style=for-the-badge&logo=verilog&logoColor=white" />
      <img src="https://img.shields.io/badge/FreeRTOS-000000?style=for-the-badge" />
    </td>
  </tr>
  <tr>
    <td align="left" valign="middle"><b>Edge AI / ML</b></td>
    <td valign="middle">
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white" />
      <img src="https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
      <img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" />
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
      <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
      <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="left" valign="middle"><b>Tools</b></td>
    <td valign="middle">
      <img src="https://img.shields.io/badge/STM32CubeIDE-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" />
      <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/OpenOCD-000000?style=for-the-badge" />
      <img src="https://img.shields.io/badge/Xilinx_Vivado-232F3E?style=for-the-badge&logo=amd&logoColor=white" />
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
    </td>
  </tr>
</table>

Also comfortable with DSA in C++ (Striver A2Z, ~150 problems).

## 🐍 Contribution Snake
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Shaurya-singh21/Shaurya-singh21/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Shaurya-singh21/Shaurya-singh21/output/github-snake.svg">
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/Shaurya-singh21/Shaurya-singh21/output/github-snake.svg">
</picture>

## 🗓️ 3D Contribution Calendar
![3D contribution calendar](https://raw.githubusercontent.com/Shaurya-singh21/Shaurya-singh21/main/profile-3d-contrib/profile-night-green.svg)

## 🤝 Let's Connect
Building or hiring for embedded firmware / edge AI work — reach out.
