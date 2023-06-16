## Hopireike Kernel
* Kernel name: Hopireika-Sunflower
* Device name: Redmi Note 9 [merlin]
* Linux version: 4.14.317
* Build user: Hoppless
* Build host: Github-Action
* Compiler name: aarch64-elf-gcc (Fortune GCC) 14.0.0 20230613 (Bleeding Edge)

## Changelogs build 16062023
* tcp_westwood: tune up a bit
* tcp_westwood: make 'rtt_min' and 'init_rtt' tunables and remove HZ dependency
* defconfig: Switch to PELT 12ms
* sched/core: Fix rq clock warning in sched_migrate_to_cpumask_end()
* sched/idle: Micro-optimize the idle loop
* sched: Add API to migrate the current process to a given cpumask
* kernel: Warn when an IRQ's affinity notifier gets overwritten
* kernel: Only set one CPU in the default IRQ affinity mask
* kernel: Don't allow IRQ affinity masks to have more than one CPU
* drm: Affine IRQ to the big CPU cluster
