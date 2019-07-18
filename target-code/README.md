# target-code

## 目录结构

- [raid-code](./raid-code)
  - [linux-4.19.36/drivers/md](./raid-code/linux-4.19.36/md): 内核态ko
  - [mdadm-4.1-rc2.0.2](./raid-code/mdadm-4.1-rc2.0.2): 用户态管理工具
- [network-driver](./network-driver)
  - [linux-4.19.36](./network-driver/linux-4.19.36): linux kernel 下的 [i40e](./network-driver/linux-4.19.36/i40e) / [i40evf](./network-driver/linux-4.19.36/i40evf) / [ixgbe](./network-driver/linux-4.19.36/ixgbe) / [ixgbevf](./network-driver/linux-4.19.36/ixgbevf) 驱动
  - [dpdk-19.05](./network-driver/dpdk-19.05): dpdk 下的 [i40e](./network-driver/dpdk-19.05/i40e) / [ixgbe](./network-driver/dpdk-19.05/ixgbe) / [mlx4](./network-driver/dpdk-19.05/mlx4) / [mlx5](./network-driver/dpdk-19.05/mlx5) 驱动

## 相关链接

### mdadm-4.1-rc2.0.2

mdadm-4.1-rc2.0.2 相关代码可在以下两个链接处找到.

- [https://rpmfind.net](https://rpmfind.net/linux/RPM/fedora/29/x86_64/m/mdadm-4.1-rc2.0.2.fc29.x86_64.html)
- [https://mirrors.edge.kernel.org](https://mirrors.edge.kernel.org/pub/linux/utils/raid/mdadm/)

### linux-kernel

- [Github - torvalds/linux](https://github.com/torvalds/linux)

### ixgbe/i40e/mlx

三者都可在 [dpdk](https://git.dpdk.org/dpdk/) 的 drivers/net/ 目录下找到. 但同时 ixgbe/i40e 也存在于 [linux-kernel](https://github.com/torvalds/linux) 的 drivers/net/ethernet/intel/ 目录下, 而 mlx 不在.
