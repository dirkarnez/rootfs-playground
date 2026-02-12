rootfs-playground
=================
| Feature        | Initrd (Initial RAM Disk)   | Initramfs (Initial RAM Filesystem) |
|----------------|-----------------------------|------------------------------------|
| Type           | Block Device (image)        | CPIO Archive (tmpfs)               |
| Size           | Fixed                       | Dynamic (Flexible)                 |
| Kernel Support | 2.4 and earlier             | 2.6 and newer                      |
| Complexity     | Higher (requires FS driver) | Lower (simpler, faster)            |
- [venomlinux/mkinitramfs: script to create initramfs image for linux system and livecd](https://github.com/venomlinux/mkinitramfs)
- [ramdisk、ramfs、tmpfs、initramfs和rootfs内存文件系统概念_ramdisk和initramfs-CSDN博客](https://blog.csdn.net/lanhuazui10/article/details/144067909)
- https://ctf-wiki.org/pwn/linux/kernel-mode/environment/qemu-emulate/#_3
- https://github.com/csmart/custom-initramfs/blob/master/create_initramfs.sh
- https://github.com/ntegan/basic_initramfs
- https://github.com/h-yamamo/minidebian/blob/bookworm/make_initrd
- https://github.com/peaclab/linux-initramfs
- https://github.com/ds-hwang/initramfs-image-maker
- https://github.com/t00sh/vm-make
- [ramdisk配置、解压、创建rootfs、启动简单分析 - ArnoldLu - 博客园](https://www.cnblogs.com/arnoldlu/p/10986583.html)
- [linux - The difference between initrd and initramfs - Stack Overflow](https://stackoverflow.com/questions/10603104/the-difference-between-initrd-and-initramfs)
- [bootparam(7) - Linux manual page](https://man7.org/linux/man-pages/man7/bootparam.7.html)
- [bootargs常用属性项_blkdevparts-CSDN博客](https://blog.csdn.net/weixin_42418557/article/details/89220785)
- [内存文件系统ramdisk_initramfs - yuxi_o - 博客园](https://www.cnblogs.com/embedded-linux/p/4823864.html)

### Minimal
- [**U-Boot on a virtual ARM machine using QEMU**](https://lnxblog.github.io/2019/02/17/uboot-arm-qemu.html)
