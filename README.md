Linux kernel source for qualcomm msm used in nexus 7 2nd (2013) tablets modified for installation in battery-less mode.

Build steps:

1. Download liarno gcc for cortex arm from here: https://github.com/Christopher83/arm-cortex_a15-linux-gnueabihf-linaro_4.9
2. Open bash shell and type folowing commands:
export ARCH=arm
export CROSS_COMPILE=arm-eabi-
export PATH=/path/to/cortex/gcc/arm-cortex_a15-linux-gnueabihf-linaro_4.9/bin:$PATH
make mrproper
make flo_defconfig
make






 