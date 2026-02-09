rootfs-playground
=================
| Feature        | Initrd (Initial RAM Disk)   | Initramfs (Initial RAM Filesystem) |
|----------------|-----------------------------|------------------------------------|
| Type           | Block Device (image)        | CPIO Archive (tmpfs)               |
| Size           | Fixed                       | Dynamic (Flexible)                 |
| Kernel Support | 2.4 and earlier             | 2.6 and newer                      |
| Complexity     | Higher (requires FS driver) | Lower (simpler, faster)            |


- https://ctf-wiki.org/pwn/linux/kernel-mode/environment/qemu-emulate/#_3
- https://github.com/csmart/custom-initramfs/blob/master/create_initramfs.sh
- https://github.com/ntegan/basic_initramfs
- https://github.com/h-yamamo/minidebian/blob/bookworm/make_initrd
- https://github.com/peaclab/linux-initramfs
- https://github.com/ds-hwang/initramfs-image-maker
- https://github.com/t00sh/vm-make

### Minimal
- [**U-Boot on a virtual ARM machine using QEMU**](https://lnxblog.github.io/2019/02/17/uboot-arm-qemu.html)
