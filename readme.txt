1. cd /home/hjc/work/develop/upstream/buildroot
2. make rk3399_defconfig
3. make menuconfig
4. make savedefconfig
5. make
6. outut rootfs: output/images/rootfs.cpio.lz4 

if update libdrm
1. make libdrm-rebuild
2. make
