<h1 align="center">Hi there 👋, I'm w-leee</h1>
<p align="center"><b>AI Algorithm Deployment & C++ Systems Engineer</b></p>

---
### 💻 双系统开发环境 / Dev Environment

> 🪟 **Windows 原生层 (应用与服务)**
> ![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=flat-square&logo=python&logoColor=white)
> ![Java](https://img.shields.io/badge/Java-17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
> ![C++](https://img.shields.io/badge/C++-GCC_11.2-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
> ![Node.js](https://img.shields.io/badge/Node.js-v22-339933?style=flat-square&logo=nodedotjs&logoColor=white)

> 🐧 **WSL2 Linux 环境 (底层与部署)**
> ![Ubuntu](https://img.shields.io/badge/Ubuntu-26.04-E95420?style=flat-square&logo=ubuntu&logoColor=white)
> ![CUDA](https://img.shields.io/badge/CUDA-12.6-76B900?style=flat-square&logo=nvidia&logoColor=white)
> ![TensorRT](https://img.shields.io/badge/TensorRT-10.7-76B900?style=flat-square&logo=nvidia&logoColor=white)
> ![Docker](https://img.shields.io/badge/Docker-29.8-2496ED?style=flat-square&logo=docker&logoColor=white)

<details>
<summary><b>👉 点击查看完整环境基准档案 (Benchmark)</b></summary>
<br>

**🪟 Windows Side:**
*   **Python**: `D:\python` (全局唯一环境), 中科大镜像源, 核心依赖包含 FastAPI/Pandas 等
*   **Java**: `D:\Environment\jdk-17` + Maven 独立仓库配置
*   **C/C++**: MinGW GCC 11.2 + CMake 3.27 + GDB 11.2
*   **Node.js**: 淘宝镜像源, 全局包路径重定向至 D 盘
*   **基建**: Git / Docker Desktop / 本地 MySQL 与 Redis

**🐧 WSL2 Linux Side:**
*   **系统**: Ubuntu 26.04, 独立 1TB 虚拟磁盘
*   **工具链**: GCC 15.2 + CMake 4.2 + GDB 17.1
*   **AI 生态**: PyTorch 2.5.1 + TensorRT 10.7 + OpenCV 5.0
*   **硬件**: RTX 3050 Laptop (CUDA 状态正常)
*   **依赖配置**: TensorRT C++ SDK 已软链接至 `/usr/local/`

</details>

---

### 🔥 旗舰项目 / Featured Project

#### 🦾 [YOLOv8 TensorRT 工业缺陷检测](https://github.com/w-leee/yolo-trt-defect-detection)
基于 YOLOv8 + ONNX + TensorRT 的混凝土裂缝实时检测与边缘推理优化。
*   **性能表现**: C++ 端到端耗时 **4.45 ms**，峰值 **224 FPS** (RTX 3050 Laptop)。
*   **核心技术**: FP16/INT8 量化、手写 DFL 解码与 NMS、C++ 端零 Python 依赖。
*   **技术栈**: `C++` `Python` `TensorRT` `CUDA` `OpenCV`

---

<p align="center">
  <i>"Talk is cheap. Show me the code." —— Linus Torvalds</i>
</p>
