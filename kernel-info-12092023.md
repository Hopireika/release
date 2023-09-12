## Hopireika Kernel
* Kernel name: Hopireika-Trixila
* Device name: Redmi Note 9 [merlin]
* Linux version: 4.14.325
* Build user: Kizziama
* Build host: Arch Linux
* Compiler name: Fortune clang version 18.0.0

## Changelogs build 12092023
* kernel-build: Increase output changelogs to 20
* kernel-build: Enable Clang LTO and Polly optimization
* drivers/input: touchscreen: Affine all Xiaomi touchscreen IRQs to big CPU
* drivers/input: goodix-fp: Affine IRQ to big CPU
* input: fpc1020: Affine IRQs to big CPU
* kernel: Affine hwcomposer to big CPUs
* ARM64: configs: Setup big.LITTLE CPU Masks
* kernel: irq: Switch to bi-cluster API for marking IRQ threads as critical
* kernel: Add tri-cluster API to affine IRQs and kthreads to fast CPUs
* cpumask: Add cpumasks for big and LITTLE CPU clusters
* mediatek: power/mt6768: gpufreq: Unlock all freq
* nediatek: power/mt6768: GPU: increase total available freq from 31 to 35 freq
* mediatek: power/mt6768: GPU: add more freq (max 1100Mhz)
* mediatek: power/mt6768: Underclock min freq from 850 to 500
* Makefile: Rework Polly optimizer flags
* Makefile: LTO Tweaks
* Makefile: Set --lto-O3 LLD linker flag when building with clang LTO
* Makefile: Actually use LLVM assembler
* Makefile: Use O3 optimization level for Clang LTO
* kbuild: Add support for LLVM's Polly optimizer
