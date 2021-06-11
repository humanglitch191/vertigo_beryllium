# Vertigo Kernel for Poco F1

![logo](https://i.imgur.com/qUoLgdl.jpg "logo")

Current version: `Vertigo v1.4-crash`

> _starts playing **crash** by EDEN_

## Features: 
* PELT Kernel. 
* Default to power efficient workqueues. 
* Sultan's perf critical IRQ framework to affine fast CPUs. 
* Sultan's simple low memory killer. 
* RCU Upstream from 4.14.
* Disabled a lot of debug drivers that are not required in production builds. 
* Ships with LSE Atomics, Fast Multiplier, Optimized In-lining, Queued Spinlocks, Dead-Code-Elimination.
* Disabled QTI Core Control, Core Rotate. 
* Disabled useless governors. 
* Updated energy model with accurate busy costs and efficiency. 
* Removed xiaomi early display hacks (mostly debug)
* Suppressed verbose during boot, Disabled broken IRQ monitoring, Disabled expedited RCU Grace periods after init. 
* Disabled crc check. 
* Switched to Util clamp with uclamp assist to set values on init. Schedtune is disabled. 
* Shipped with Berkley Packet Filter Just in Time compiler. 
* Default TCP is BBR. 
* Default timer frequency is 100hz.
* Ships with kcal (default 231).
* Switched to srandom. 
* Compiled with GCC - https://github.com/mvaisakh/gcc-build with optimizations for sdm845 (cortex.a75 cortex.a55).
* Switched to s2idle (suspend-to-idle).
* Patched cmdline flags for safetynet (androidboot.flash.locked, androidboot.verifiedbootstate, androidboot.veritymode).
* Reduced qcacld-3.0 wakelock.
* Disabled few debug stuff of qcacld-3.0.
* Updated touchscreen (nt36xx) drivers from CAF. 
* Added sound control driver. 

## Telegram releases channel: 
- [Telegram Channel](https://t.me/vertigo_releases)
