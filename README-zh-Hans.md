# XMRig

[![GitHub All Releases](https://img.shields.io/github/downloads/genshinzmnl/acexmrig/total.svg)](https://github.com/C3Pool/xmrig/releases) 
[![GitHub release](https://img.shields.io/github/release/genshinzmnl/acexmrig/all.svg)](https://github.com/C3Pool/xmrig/releases) 
[![GitHub Release Date](https://img.shields.io/github/release-date/genshinzmnl/acexmrig.svg)](https://github.com/C3Pool/xmrig/releases) 
[![GitHub license](https://img.shields.io/github/license/genshinzmnl/acexmrig.svg)](https://github.com/C3Pool/xmrig/blob/master/LICENSE) 
[![GitHub stars](https://img.shields.io/github/stars/genshinzmnl/acexmrig.svg)](https://github.com/C3Pool/xmrig/stargazers) 
[![GitHub forks](https://img.shields.io/github/forks/genshinzmnl/acexmrig.svg)](https://github.com/C3Pool/xmrig/network) 

[English](README.md)

XMRig 是一个高性能、开源、跨平台的 RandomX、KawPow、CryptoNight 和 [GhostRider](https://github.com/genshinzmnl/acexmrig/tree/master/src/crypto/ghostrider#readme) 统一 CPU/GPU 挖矿软件和 [RandomX 基准测试](https://xmrig.com/benchmark)。官方二进制文件适用于 Windows、Linux、macOS 和 FreeBSD。

## 支持的设备
- **CPU** (x86/x64/ARMv7/ARMv8)
- **OpenCL** 用于 AMD GPU。
- **CUDA** 用于 NVIDIA GPU，通过外部 [CUDA 插件](https://github.com/xmrig/xmrig-cuda)。

## 下载
* **[二进制发布版](https://github.com/genshinzmnl/acexmrig/releases)** 
* **[从源代码构建](https://xmrig.com/docs/miner/build)** 

## 这是哪个项目的fork？
* **我在c3pool提供的xmrig-C3中修改了部分代码。**

## 我修改了什么
* **1.在pool.cpp中彻底移除了抽水。**
* **2.修改了图标**
* **3.修改了默认配置文件**
* **4.移除了旧的抽水文件**
* **5.修复了部分错误**
* **6.提升了一点的挖矿速度（很小，像误差一样）**

## 使用
配置矿工的首选方式是 [JSON 配置文件](https://xmrig.com/docs/miner/config)，因为它更灵活且对人类更友好。[命令行界面](https://xmrig.com/docs/miner/command-line-options) 并不涵盖所有功能，例如不同算法的挖矿配置文件。通过编辑配置文件或执行 [API](https://xmrig.com/docs/miner/api) 调用，可以在不重启矿工的情况下更改重要选项。

* **[向导](https://xmrig.com/wizard)** 帮助您为矿工创建初始配置。
* **[工人](http://workers.xmrig.info)** 通过 HTTP API 帮助管理您的矿工。

## 捐赠
* 默认捐赠 0%
* XMRig原作者钱包地址: `48edfHu7V9Z84YzzMa6fUueoELZ9ZRXq9VetWzYGzKt52XU5xvqgzYnDK9URnRoJMk1j8nLwEVsaSWJ4fhdUyZijBGUicoD`
* 我的捐赠地址: `49CxrVYrUuBH1izponLxzh5oN4qZCYPgR1QhifcuP4WVKHcXmhLNLA92L3yM7KvpsoDaXcERdEhX45sgxTYLnUVcE1A3zYa`

## 开发者
* **[xmrig](https://github.com/xmrig)** 
* **[sech1](https://github.com/SChernykh)** 

## 联系方式
* support@xmrig.com
* [reddit](https://www.reddit.com/user/XMRig/) 
* [twitter](https://twitter.com/xmrig_dev) 