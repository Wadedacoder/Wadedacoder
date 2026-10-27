### Hi, I'm Dev 👋

Senior Software Engineer at **Infoedge**, working on backend performance (cut video-service latency from 200 ms to 70 ms). I come from computer graphics: CUDA Gaussian-splatting tooling at ÉTS Montréal and an OpenXR/DirectX 11 CT-scan viewer at IIIT Delhi's graphics group. Now moving toward **GPU kernels and LLM inference**.

#### Featured work

| Project | What it is | Measured result |
|---|---|---|
| [triton-kernels](https://github.com/Wadedacoder/triton-kernels) | Kernel worklog: fused row-wise softmax in Triton, with fp32/fp16 correctness tests | 93–95% of peak DRAM bandwidth; 3.9–4.4x faster than unfused PyTorch |
| [Cuda-Raytracer](https://github.com/Wadedacoder/Cuda-Raytracer) | One-thread-per-pixel CUDA ray tracer, benchmarked against the same code on the CPU | 11–19x faster than 16 CPU threads (kernel only), matching output within 1/255 |
| [RayTracer](https://github.com/Wadedacoder/RayTracer) | Ray tracer in an OpenGL fragment shader, with a C++ CPU port for comparison | 90–155x faster than the 16-thread CPU port |
| [PBDynamics](https://github.com/Wadedacoder/PBDynamics) | Position Based Dynamics cloth engine (C++/OpenGL), profiled per stage | CPU constraint solver is 80–90% of frame time; 4,096-particle cloth at 4.0 ms per frame |
| [HcArgoLib](https://github.com/Wadedacoder/HcArgoLib) | Work-stealing task-parallel runtime in C/C++ | Up to 5x faster than serial execution |
| [Orderbook](https://github.com/Wadedacoder/Orderbook) | Stock-exchange order book: Django + Redis sorted sets for price-time matching, React UI | — |

All GPU numbers were measured on an RTX 3050 Laptop GPU; each repo has its raw results and the scripts to reproduce them.

**Currently learning:** CUDA, Triton, LLM inference

**Tools:** C++ · CUDA · Triton · PyTorch · OpenGL · Python · Java · Redis · Kafka
