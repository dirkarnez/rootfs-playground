inittab
=======
- [imx_openwrt/target/linux/uml/base-files/etc/inittab at 87898e57136cbab87cd896aaee0faa3fa86b4962 · nxp-imx/imx_openwrt](https://github.com/nxp-imx/imx_openwrt/blob/87898e57136cbab87cd896aaee0faa3fa86b4962/target/linux/uml/base-files/etc/inittab)
  - ```
    # Copyright (c) 2013 The Linux Foundation. All rights reserved.
    ::sysinit:/etc/init.d/rcS S boot
    ::shutdown:/etc/init.d/rcS K shutdown
    tty0::askfirst:/usr/libexec/login.sh
    ```
