# Obaid Miah

**Systems & Kernel Engineer**
C++ · CUDA · Hardware-coupled software · Los Angeles

Principal Software Engineer at Northrop Grumman. UCLA EE.
I write software that understands the hardware beneath it.
FPGA device drivers, DMA pipelines, ISRs, VxWorks BSP, real-time
datapath control. Now applying that hardware-first instinct to
GPU kernel engineering and AI infrastructure.

## What I do

**Former job — embedded.** FPGA device drivers in C++,
interrupt-driven datapath control, DMA ingress / egress pipelines,
VxWorks BSP, MMIO register-level FPGA programming, real-time
demod / mod pipeline control.

**Off-hours — systems C++ and GPU kernels.** Distributed-systems
projects to stretch into storage and networking; CUDA / Triton
kernel work to translate hardware-first thinking into AI infra.

## Stack
**Core:** C, C++, CUDA, Python
**GPU / Kernel:** CUDA kernel optimization, Triton, roofline analysis, warp / occupancy tuning
**Embedded:** VxWorks, BSP development, DMA + ISR programming, FPGA driver interfacing, MMIO
**Build / Test:** CMake, GoogleTest, Docker, ASan / UBSan
**Tools:** Git, gRPC, Protocol Buffers, vcpkg

## Pinned work

- **[Key_Value_In_Memory](https://github.com/ObaidMiah/Key_Value_In_Memory)** —
  Durable, replicated key-value store written from scratch in C++.
  CRC-framed write-ahead log, fsync-per-write recovery, gRPC wire
  protocol, 3-node replicated cluster via docker-compose, crash-recovery
  test harness, CI building Debug + Release under sanitizers.

- **[Custom-STL-and-Smart-Pointer-Library](https://github.com/ObaidMiah/Custom-STL-and-Smart-Pointer-Library)** —
  Hand-written containers and smart pointers covered by GoogleTest.
  RAII, move semantics, allocator-aware design.

- **[ObjectDetection](https://github.com/ObaidMiah/ObjectDetection)** —
  Hough Transform shape detection for real-time image analysis on
  embedded hardware.

- **[SpeechRecognition](https://github.com/ObaidMiah/SpeechRecognition)** —
  Neural-network vowel classifier running on a DSP.

## Currently building

- Tiled shared-memory CUDA matmul, benchmarked against cuBLAS on A100
- Custom CUDA / C++ PyTorch extension wired into autograd
- Flash-Attention-style kernel with SRAM-resident tiles + roofline analysis

## Elsewhere

- Site — [obaidmiah.com](https://obaidmiah.com)
- LinkedIn — [obaid-miah](https://www.linkedin.com/in/obaid-miah/)
- Email — obaidmiah@gmail.com
