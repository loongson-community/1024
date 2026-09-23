# 1024 Project Hardware Application

## 主要用途 (Main Purpose)
上游集成 / 社区适配

Porting and optimizing a high-performance machine learning framework ([Magnetron](https://github.com/MarioSieg/magnetron)) to LoongArch, including SIMD kernel implementation and CPU inference optimization.

---

## 预期效果 (Expected Outcome)

- Port Magnetron (C-based ML framework) to LoongArch  
- Implement LASX SIMD backend for tensor operations  
- Run transformer inference models (e.g. Qwen family) on Loongson CPUs  
- Benchmark performance vs x86 (AVX512) and ARM (NEON)  
- Identify performance bottlenecks and contribute optimizations  
- Publish results and share findings with the LoongArch community  

---

## 申请设备 (Requested Hardware)

**Preferred:**
- 主机板卡-3A6000双网卡  

**Alternative:**
- 整机-3A6000NUC  

---

## 身份信息 (Identity)

Mario Sieg  

- Author & Maintainer of [Magnetron ML Framework](https://github.com/MarioSieg/magnetron)  
- Software Engineer (CPU/CUDA Kernel Development) at Prime Intellect  
- Student at TU Berlin (Computer Science, Mathematics)  

---

## 联系方式 (Contact)

- Email: mario.sieg.64@gmail.com  
- GitHub: https://github.com/MarioSieg  
- X: https://x.com/mario_neo  

---

## 备注 (Additional Information)

[Magnetron](https://github.com/MarioSieg/magnetron) is a lightweight, high-performance machine learning framework written in C with a Python interface. It features a custom tensor engine, SIMD vectorization (AVX2 / AVX-512 / NEON), and a strong focus on performance and minimal dependencies.

The framework already supports transformer inference (e.g. Qwen models) on CPU. Current development focuses on improving performance scaling, kernel fusion, and architecture-specific optimizations.

By porting Magnetron to LoongArch, I aim to:

- provide real-world ML inference benchmarks on Loongson CPUs  
- implement optimized LASX SIMD kernels  
- evaluate LoongArch as a platform for modern AI workloads  
- improve compatibility and performance of ML software on LoongArch  

I am willing to:

- share benchmark results publicly  
- contribute fixes and optimizations  
- participate in community discussions or technical reports  

This work directly supports the LoongArch ecosystem by enabling efficient machine learning workloads on Loongson hardware and improving developer adoption.
