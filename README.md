<div align="center">

# Hi, I'm Shaurya Singh 👋
### Embedded Firmware & Edge AI Engineer

Bare-metal ARM Cortex-M4 firmware and on-device inference — bridging raw silicon and edge intelligence.

[LinkedIn](https://linkedin.com/in/shaurya-singh-16270b336) · [Email](mailto:shauryasingh.uno@gmail.com) · [GitHub](https://github.com/Shaurya-singh21)

</div>

---

## 🔭 Current Focus
- Building a two-platform edge inference benchmark: same model on STM32 and Jetson, with latency/throughput/power and INT8 accuracy-delta numbers
- Deepening FreeRTOS internals — synchronization primitives, ISR/DMA integration
- Working through CUDA fundamentals (naive → tiled shared-memory → cuBLAS) ahead of TensorRT deployment
- Open to embedded firmware / edge AI internships

## 🛠️ Featured Projects

### Custom UART Bootloader + IAP Firmware Update
Dual-partition bare-metal bootloader on STM32F446RE with CRC32 boot validation via the hardware CRC peripheral, selective sector erase, and a Python/pyserial host tool that streams firmware in checksummed 256-byte chunks over UART.
- **Stack:** STM32F446RE (zero-HAL, register-level), C, Python
- **Status:** Complete — full erase/transfer/flash/jump cycle verified end-to-end
- **Code:** [github.com/Shaurya-singh21/Custom_IAP_Bootloader](https://github.com/Shaurya-singh21/Custom_IAP_Bootloader)

### FreeRTOS Motor Bearing Fault Detection
Real-time fault classification (healthy / imbalance / bearing fault / transient shock) on a spinning motor. MPU6050 accelerometer sampled via I2C+DMA double-buffering, on-device FFT feature extraction, Random Forest inference (15 features, 4 classes) running inside a multi-task FreeRTOS pipeline, results out over UART and OLED.
- **Stack:** STM32F446RE, FreeRTOS, C, scikit-learn (offline training)
- **Status:** In progress — inference pipeline running on-device; debugging an I2C/DMA display sync issue
- **Code:** `[ADD-LINK]`

### DMA-Driven Environmental Monitoring Platform
Nine-peripheral, zero-HAL bare-metal platform: dual DMA channels, ADC, four timers, I2C, UART, GPIO/EXTI, and an SSD1306 OLED. Closed-loop actuation — vents and a fan driven directly off temperature thresholds.
- **Stack:** STM32F446RE (register-level, no HAL)
- **Status:** Complete
- **Code:** `[ADD-LINK]`

### CUDA MNIST Inference Benchmark
Three-stage CUDA C++ inference benchmark for a PyTorch-trained MLP: hand-written naive kernels → tiled shared-memory kernels → cuBLAS, profiled with Nsight Compute. Built as CUDA fundamentals practice ahead of Jetson/TensorRT work.
- **Stack:** CUDA C++, PyTorch, Nsight Compute
- **Status:** In progress — naive version verified correct, tiled version in development
- **Code:** `[ADD-LINK]`

### Neuromorphic FPGA SNN Accelerator — ISRO URSC Research Internship
Six-stage pipelined spiking neural network accelerator on a Xilinx Virtex-7, evaluated against a CNN baseline: 95.0% accuracy, 7x fewer parameters, 39% lower energy.
- **Stack:** Verilog RTL, Xilinx Virtex-7
- **Status:** Complete (internship deliverable)
- **Code:** `[ADD-LINK if public]`

## 💻 Tech Stack

**Embedded / Systems**
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![ARM Cortex-M](https://img.shields.io/badge/ARM%20Cortex--M-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-245464?style=for-the-badge&logo=verilog&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-000000?style=for-the-badge)

**Edge AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

**Tools**
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)

Also comfortable with DSA in C++ (Striver A2Z, ~150 problems).
## 🐍 Contribution Snake
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Shaurya-singh21/Shaurya-singh21/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Shaurya-singh21/Shaurya-singh21/output/github-snake.svg">
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/Shaurya-singh21/Shaurya-singh21/output/github-snake.svg">
</picture>
## 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Shaurya-singh21&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

## 🤝 Let's Connect
Building or hiring for embedded firmware / edge AI work — reach out.
