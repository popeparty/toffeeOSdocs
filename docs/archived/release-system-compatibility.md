---
title: System Compatibility
---

## toffeeOS Developer Version (toffeeOS) system compatibility
Due to the upcoming [x86 support deprecation](https://github.com/onetwentyfour/toffeeOSdocs/blob/master/docs/releases/x86-support-deprecation.md), we recommend installing toffeeOS Developer Version on a 64-bit processor. 

The requirements below are subject to change at any time.

## toffeeOS Developer Version 2.0 and later
### RAM
- Minimum: 4GB
- Recommended: 16GB

### Components
- CPU
  - **Intel**: Must be a 64-bit processor, released in 2014 or later.
  - **AMD**: Must be a 64-bit processor, Ryzen 1000 series or later only.
  - **Apple**: Must be a 64-bit processor, M1/M2 families only.
- Discrete GPU (x86_64 on Intel/AMD 64-bit only): NVIDIA GPU launched in 2016 or later.
  - Specifics: GTX 1050 or later, GT cards are no longer supported by our team officially.
  - Discrete GPUs *must* support Vulkan 1.4 or later.
  
### Storage
  - Minimum storage space needed for install: 15 GB
  - Recommended storage space (after install): 256+ GB SSD  
  - Hard/Fusion/Hybrid Drives are **NOT** supported.  

## toffeeOS Developer Version 1.6.1 and later

### RAM
- Minimum: 4GB
- Recommended: 8GB

### Components
- CPU: Intel CPU launched in 2013 or later; AMD A8 APUs released in 2014 and later, and Ryzen 1000 and later.
  - CPU and Motherboard (MBO) pairing must also support UEFI. CPU and MBO pairings without UEFI cannot boot the OS.
  - Intel processors from 2012 and earlier are no longer supported and will remain on toffeeOS Developer Version 1.5 non-LTS.
  - We do not support AMD CPUs prior to Ryzen 1000 or AMD APUs prior to 2014 A8 due to technical limitations.
- GPU (64-bit only): NVIDIA GPU launched in 2014 or later.
  - Specifics: GT 705 or later, GTX 745 or later, and GTX Titan or later. 
  - GPU must support Vulkan.

### Storage
- Minimum storage space needed for install: 75 GB
- Recommended storage space (after install): 320+ GB HDD/SSD  
- Fusion/Hybrid drives are **NOT** supported.  

## toffeeOS Developer Version 1.5.x and earlier

### RAM
- Minimum: 728MB (32-bit), 2GB (64-bit)
- Maximum (32-bit only): 4GB
- Recommended: 4GB (both)

### Components
- CPU: Intel CPU launched in 2011 or later; AMD A8 APUs released in 2014 and later, and Ryzen 1000 and later.
  - CPU and Motherboard (MBO) pairing must also support UEFI. CPU and MBO pairings without UEFI cannot boot the OS.
  - We do not support the 2010 Intel Core 2 Duo or earlier due to technical limitations.
  - We do not support AMD CPUs prior to Ryzen 1000 or AMD APUs prior to 2014 A8 due to technical limitations.
- GPU (64-bit only): NVIDIA GPU launched in 2014 or later.
  - Specifics: GT 705 or later, GTX 745 or later, and GTX Titan or later. 

### Storage
- Minimum needed for install: 26GB (32-bit); 46GB (64-bit)
- Recommended storage: 256 GB HDD/SSD  
Fusion/Hybrid drives are no longer supported.  
