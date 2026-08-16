# Obaid Miah

**Principal Software Engineer**
C++ · CUDA · Hardware-coupled software · Los Angeles

Former Principal Software Engineer at Northrop Grumman. UCLA EE.
I write software that understands the hardware beneath it.
FPGA device drivers, DMA pipelines, ISRs, VxWorks BSP, real-time
datapath control. Now applying that hardware-first instinct to go deep in C++, distributed systems, and backend services. 

## What I do

**Former job — Embedded.** FPGA device drivers in C++,
interrupt-driven datapath control, DMA ingress / egress pipelines,
VxWorks BSP, MMIO register-level FPGA programming, real-time
demod / mod pipeline control.

**Off-hours — systems C++ and backend services.** Distributed-systems
projects to stretch into storage, networking, and latency.

## Stack
- **Core:** C, C++, CUDA, Python

- **GPU / Kernel:** CUDA kernel optimization, Triton, roofline analysis, warp / occupancy tuning

- **Embedded:** VxWorks, BSP development, DMA + ISR programming, FPGA driver interfacing, MMIO

- **Build / Test:** CMake, GoogleTest, Docker, ASan / UBSan

- **Tools:** Git, gRPC, Protocol Buffers, vcpkg

## Pinned work

- **[key-value-in-memory](https://github.com/ObaidMiah/Key_Value_In_Memory)** —
  Durable, replicated key-value store written from scratch in C++.
  CRC-framed write-ahead log, fsync-per-write recovery, gRPC wire
  protocol, 2-node leader-follower replication, crash-recovery
  test harness, CI building Debug + Release under sanitizers.

- **[multi-thread-http-server](https://github.com/ObaidMiah/multi-thread-http-server)** —
  Multithreaded HTTP/1.1 server written from scratch in C++ on raw POSIX sockets. Fixed thread pool with a mutex/condition-
  variable work queue, keep-alive connections, query/header/body parsing, static file serving, JSON REST API, graceful SIGINT
  shutdown with worker draining, and curl-based smoke tests.

- **[custom-stl-and-smart-pointer-library](https://github.com/ObaidMiah/Custom-STL-and-Smart-Pointer-Library)** —
  Implemented core logic of containers and smart pointers covered by GoogleTest.
  RAII, move semantics, manual memory management design.

- **[object-detection](https://github.com/ObaidMiah/ObjectDetection)** —
  Hough Transform shape detection for real-time image analysis on
  embedded hardware.

- **[speech-recognition](https://github.com/ObaidMiah/SpeechRecognition)** —
  Neural-network vowel classifier running on a DSP.

- **[mobile-robot](https://github.com/ObaidMiah/MobileRobot)** —
  Voice-controlled robot. On-device speech recognition (FFT + MFCC +
  neural-network classifier) running on a TI DSP; recognized commands
  relayed via an nRF24L01 wireless link to an Arduino motor controller.
  C + Arduino across three boards (LCDK / transmitter / receiver).

## Currently building

- Tiled shared-memory CUDA matmul, benchmarked against cuBLAS on A100
- Custom CUDA / C++ PyTorch extension wired into autograd
- Flash-Attention-style kernel with SRAM-resident tiles + roofline analysis

## Elsewhere

- Site — [obaidmiah.com](https://obaidmiah.com)
- LinkedIn — [obaid-miah](https://www.linkedin.com/in/obaid-miah/)
- Email — obaidmiah@gmail.com
- Twitter — [obaid_miah](https://x.com/Obaid_Miah)
