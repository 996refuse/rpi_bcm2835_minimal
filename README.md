# RPI BCM2835 MINIMAL

树莓派bcm2835最小系统

# FEATURES


1. 删除了网络相关组件
2. 文件系统仅支持ext2
3. 删除Linux kernel module 支持
4. 减小image size
5. 开启gdb script

# USAGE

```
git clone https://github.com/buildroot/buildroot
make BR2_EXTERNAL=../rpi_bcm2835_minimal/ rpi_bcm2835_minimal_defconfig
make source # if your network is not stable
make
```

