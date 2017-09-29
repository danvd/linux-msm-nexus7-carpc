Linux kernel source for qualcomm msm used in nexus 7 2nd (2013) tablets modified for installation in battery-less mode.

Build steps:

1. Download liarno gcc for cortex arm from here: https://github.com/Christopher83/arm-cortex_a15-linux-gnueabihf-linaro_4.9
2. Open bash shell
3. export ARCH=arm
4. export CROSS_COMPILE=arm-eabi-
5. export PATH=/path/to/cortex/gcc/arm-cortex_a15-linux-gnueabihf-linaro_4.9/bin:$PATH
6. make mrproper
7. make flo_defconfig
8. make






 
