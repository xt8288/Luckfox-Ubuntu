# Luckfox-Ubuntu

欢迎来到 **Luckfox Ubuntu 镜像文档库**！

> 📖 [View this document in English »](./README.md)

## 📚 简介

本仓库提供以下内容：多种 Luckfox 开发板的 Ubuntu 系统镜像使用方法，不带 eMMC 的型号需通过 MicroSD 卡烧录系统镜像启动设备，带 eMMC 的型号将系统烧录至 eMMC。

## 📁 目录结构说明

```
├── README.md             
├── README.zh-CN.md        
├── docs/
│   ├── en/
│   │   ├── RV1106/
|   |   ├── RK3506/
│   │   └── RK3566
│   └── zh-CN/
│       ├── setup.md
│       ├── usage.md
│       └── advanced.md
```

## 💻 支持的开发板

| 开发板型号   | 处理器平台 | 系统支持版本     |
| ------------ | ---------- | ---------------- |
| Core3566     | RK3566     | Ubuntu 22.04 LTS |
| Luckfox Lyra | RK3506     | Ubuntu 22.04 LTS |
| Luckfox Pico | RV1106     | Ubuntu 22.04 LTS |

## 🚀 快速入门

1. 下载对应平台的 Ubuntu 镜像；
2. 使用 SocTookit、SDDiskTool  等工具将镜像烧录至 MicroSD 卡；
3. 将 MicroSD 卡插入开发板，连接电源启动；
4. 通过串口或 SSH 访问系统，进行基本配置。

## 📥 镜像下载地址

[百度网盘]( https://pan.baidu.com/s/1p1VZJxcIn9wsNEMPU7ICFA?pwd=nd4x)
[谷歌网盘](https://drive.google.com/drive/folders/1eTNv6OGGV-p7EaZKTl0a0mbzEm4X1L73?usp=drive_link)
