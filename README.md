# Radeon-GPUProfiler

The Radeon GPU Profiler (RGP) is a ground-breaking low-level optimization tool from AMD.  It provides detailed timing information on Radeon Graphics using custom, built-in, hardware thread-tracing, allowing the developer deep inspection of GPU workloads.

This unique tool generates easy to understand visualizations of how your DirectX®12 and Vulkan® games interact with the GPU at the hardware level. Profiling a game is both a quick, and simple process using the Radeon Developer Panel and the public Crimson driver. 


## Getting Started

1. Install the latest Crimson driver (17.7.2 or newer for Windows, 17.30 for Linux).
2. Unzip/Untar the download file. The directory contains the following:
* Radeon Developer Service (RDS)
* Radeon Developer Panel (RDP)
* Radeon GPU Profiler (RGP)
3. To gather a profile from a game run the Radeon Developer Panel and follow the instructions in the Help - Help can be found in one of the following locations:
* There are two help documents in the "docs" directory (**RadeonDeveloperPanel.pdf** and **RadeonGPUProfiler.pdf**)
* Help web pages exist in the "docs" sub directory
* Help web pages can be accessed from the Help button in the Developer Panel
* Help web pages can be accessed from the Welcome screen in the Radeon GPU Profiler, or from the help menu

## Supported ASICs
* AMD Radeon™ R9 Fury and Nano series  
* AMD Radeon™ RX 400, RX 500 series
 
## Supported OS's and API's
### Windows10  
* DirectX12  
* Vulkan
    
### Windows7  
* Vulkan  - User must install latest VC 2015 redistributables from https://www.microsoft.com/en-us/download/details.aspx?id=53840
    
### Ubuntu 16.04 LTS  
* Vulkan
