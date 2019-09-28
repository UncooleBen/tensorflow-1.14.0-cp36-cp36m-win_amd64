# Personal-Built Tensorflow Package
This repository contains two packages of tensorflow. One for CPU and another for GPU. Since the general binary installed by pip doesnt't support some features (e.g. AVX, AVX2).  
Feel free to download
1. tensorflow-1.14.0-cpu.whl  
   This whl was built under my Surface Pro 5. For CPU only.  
   OS: Windows 10 1903 64-bit  
   Processor: Intel(R) Core(TM) i7-7660U  
   Architecture: amd64  
   Bazel Version: 0.26.1  
   MSVC Version: Visual Studio Buildtools 2019 14.23.28105  
   Build Option: /arch:AVX /arch:AVX2  
2. tensorflow-1.14.0-cuda10-cudnn7-gpu7.5.whl  
   This whl is built under:  
   OS: Windows 10 1903 64-bit  
   Processor:  Intel(R) Core(TM) i7-9700K  
   Architecture: amd64  
   Bazel Version: 0.24.1  
   MSVC Version: Visual Studio Buildtools 2017 15.9.16
   Build Option: /arch:AVX /arch:AVX2 /std:c++14  
   GPU CUDA Compute Capability: 7.5 
   GPU: NVIDIA GeForce RTX 2060  
   
