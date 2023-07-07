## Hopireika Kernel
* Kernel name: Hopireika-Sunflower
* Device name: Redmi Note 9 [merlin]
* Linux version: 4.14.320
* Build user: Hoppless
* Build host: Github-Action
* Compiler name: aarch64-elf-gcc (Eva GCC) 14.0.0 20230625 (Bleeding Edge)

## Changelogs build 07072023
* defconfig: regen & save
* Merge tag '4.14.320' of https://android.googlesource.com/kernel/common into base
* scripts: vmlinux: Show LTO for GCC instead of LD
* arm64: Fix section mismatch with LTO caused by ambiguous const
* Makefile: Disable aggressive loop optimisation warnings
* Makefile: Disable stringop-overread for LTO
* arm64: Allow LD_DEAD_CODE_DATA_ELIMINATION to be selected
* kbuild: Allow LD_DEAD_CODE_DATA_ELIMINATION to be selectable if enabled
* kbuild: Fix asm-generic/vmlinux.lds.h for LD_DEAD_CODE_DATA_ELIMINATION
* arm64: Inline the spin lock function family
