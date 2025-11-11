## ImmortalWrt for 斐讯 N1
- **固件格式**：不是传统的 `ext4` 或 `squashfs` 格式，而是 `btrfs` 格式，支持快照
- **后台地址**：需查询（详见下文）
- **用户名**：`root`
- **密码**：`password`
- **是否带 Docker**：根据用户选择
- **默认软件包大小**：1GB
- **内核版本**：根据用户选择
- **晶晨宝盒**：✅ 自带，用于写入 `emmc`
- **Rootfs.tar.gz 构建**：采用 ImmortalWrt 的 `ImageBuilder`
- **打包 img**：采用 `onhub/amlogic-s9xxx-openwrt` 或 `flippy-openwrt-actions`
- **默认底包位置**：https://github.com/wukongdaily/AutoBuildImmortalWrt/releases/tag/rootfs

### 注意事项
斐讯 N1 为单网口设备，网线连接路由器后，默认是自动获取 IP 的模式
请在上级路由器的 DHCP 列表中查询具体的局域网 IP
