# **FNOS_ARM-rock-4d历史版本镜像库**

<img width="1300" height="552" alt="FnNAS" src="https://github.com/user-attachments/assets/daf92398-5f75-4c74-8b55-dab31f84c3e3" />

FnNAS 是一款基于最新 Linux 内核（Debian 发行版）深度定制的操作系统。它具备出色的硬件兼容能力，全面支持主流 x86 及 Arm64 设备，支持用户自主组建 NAS 并灵活扩展外部存储。现在，您可以轻松将电视盒子的 Android TV 系统替换为 FnNAS，将其打造为一台功能强大的私有数据存储服务器。

本项目得益于众多 贡献者 的持续贡献，并在 FnNAS 官方技术专家的指导下，为搭载 Amlogic、Rockchip 和 Allwinner 芯片的电视盒子构建了 Arm64 架构适配的 FnNAS 系统。构建版本完整继承了官方系统的全部功能，支持写入 eMMC 启动以及内核在线更新。最新固件请前往 Releases 页面下载。欢迎 Fork 本项目进行个性化定制。如果本项目对您有所帮助，请点击仓库右上角的 Star ⭐ 以示支持！

## **安装 FnNAS 到 UFS模块**
先安装官方linux系统后用dd指令移植到UFS模块中去
