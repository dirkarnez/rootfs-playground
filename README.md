# rootfs-playground
| Feature        | Initrd (Initial RAM Disk)   | Initramfs (Initial RAM Filesystem) |
|----------------|-----------------------------|------------------------------------|
| Type           | Block Device (image)        | CPIO Archive (tmpfs)               |
| Size           | Fixed                       | Dynamic (Flexible)                 |
| Kernel Support | 2.4 and earlier             | 2.6 and newer                      |
| Complexity     | Higher (requires FS driver) | Lower (simpler, faster)            |


- https://ctf-wiki.org/pwn/linux/kernel-mode/environment/qemu-emulate/#_3
