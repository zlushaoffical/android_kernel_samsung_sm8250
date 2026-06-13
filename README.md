# Samsung Snapdragon 865 (SM8250) Kernel

Kernel source for Samsung Galaxy Fold 2 and other Snapdragon 865-based devices.

## Based on
- Samsung Open Source kernel
- Snapdragon 865 platform
- Android 13 base

## Building

```bash
export ARCH=arm64
export CROSS_COMPILE=aarch64-linux-android-
make f2q_defconfig
make -j$(nproc)
```

## Device Support
- Galaxy Fold 2 (f2q)

## Status
🚧 Work in Progress - Kernel integration phase
