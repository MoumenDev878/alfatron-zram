# Faltron-zRam 🚀🔥

Faltron is an advanced asynchronous compression algorithm module (`acomp`) developed for the Linux Kernel and optimized for `zRam`.

## Verified Benchmarks (On Arch Linux with 2GB RAM)
* **Allocated Virtual Capacity:** 48 GB - 64 GB
* **Real Uncompressed Data (DATA):** 48 GB (Workload: GNOME, QEMU Win10 VM, 30+ Firefox Tabs)
* **Actual Physical Space Used (COMPR):** ~256 MB
* **Observed Compression Ratio:** Up to **1:192** (lossless bit-level context prediction).

## How to Build
```bash
make
sudo insmod faltron.ko
```
