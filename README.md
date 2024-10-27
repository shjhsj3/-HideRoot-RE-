# ROOTassistant_HideRootGrass_scr<span style="color: #FF0000;">（ROOT助手隐藏Root草稿脚本）</span>

该项目是一个bash脚本，用于通过下载并安装特定的Magisk模块来隐藏Root痕迹。它特别适用于需要绕过应用检测Root权限的用户。

## 项目概述

`ROOTassistant_HideRootGrass_scr` 脚本通过自动下载并配置必要的Magisk模块，帮助用户隐藏Root状态。这使得用户可以在保持Root功能的同时，避免被应用检测到Root权限。

## 使用的Magisk模块

本项目使用的Magisk模块包括：

- **<span style="color: #0080FF;">TrickyStore</span>**：5ec1cff 用于隐藏打开的Bootloader Lock [链接](https://github.com/5ec1cff/TrickyStore/)。配置方式通过脚本的前置配置程序自动下载模块并放入依赖。
- **<span style="color: #0080FF;">Zygisk-Next</span>**：zygisk的独立实现，用于支持shamiko的运行 [链接](https://github.com/Dr-TSNG/ZygiskNext/)。配置方式通过脚本的前置配置程序自动下载模块并放入依赖。

## 适配的Magisk版本

本项目适配以下Magisk版本：

- **Magisk Alpha**
- **Magisk Kitsune Mask**
- **APatch**
- **KernelSU**

## 安装指南

1. 确保您的设备已经安装了root管理器，并处于适配的版本之一。
2. 下载`ROOTassistant_HideRootGrass_scr`脚本。
3. 将脚本复制到设备的可执行路径下，并给予执行权限。
4. 运行脚本以自动下载并配置依赖的模块达到隐藏root。

## 使用说明

在安装并设置好所有必要的依赖后，运行脚本即可开始隐藏Root痕迹。脚本会自动下载并配置<span style="color: #0080FF;">TrickyStore</span>和<span style="color: #0080FF;">Zygisk-Next</span>模块以及其他模块，无需手动干预。

## 贡献指南

如果您发现任何问题或有改进建议，欢迎通过GitHub的Issue或Pull Request功能提交。

## 维护者

0.1-1.92版本的维护者 - RE2024
1.9往后将会是RDE维护

---

*最后更新日期：2024-10-27*

---

# ROOTassistant_HideRootGrass_scr<span style="color: #FF0000;">（ROOT Assistant Hide Root Grass Script）</span>

This project is a bash script designed to hide root traces by downloading and installing specific Magisk modules. It is particularly suitable for users who need to bypass app detection of root permissions.

## Project Overview

The `ROOTassistant_HideRootGrass_scr` script assists users in hiding root status by automatically downloading and configuring the necessary Magisk modules. This allows users to maintain root functionality while avoiding detection by apps.

## Magisk Modules Used

The Magisk modules used in this project include:

- **<span style="color: #0080FF;">TrickyStore</span>**: 5ec1cff for hiding the open Bootloader Lock [Link](https://github.com/5ec1cff/TrickyStore/). The configuration is automatically downloaded and added to dependencies through the script's pre-configuration program.
- **<span style="color: #0080FF;">Zygisk-Next</span>**: An independent implementation of zygisk for supporting the operation of shamiko [Link](https://github.com/Dr-TSNG/ZygiskNext/). The configuration is automatically downloaded and added to dependencies through the script's pre-configuration program.

## Supported Magisk Versions

This project is compatible with the following Magisk versions:

- **Magisk Alpha**
- **Magisk Kitsune Mask**
- **APatch**
- **KernelSU**

## Installation Guide

1. Ensure your device has a root manager installed and is one of the supported versions.
2. Download the `ROOTassistant_HideRootGrass_scr` script.
3. Copy the script to an executable path on your device and grant execution permissions.
4. Run the script to automatically download and configure the dependent modules to hide root.

## Usage Instructions

After installing and setting up all necessary dependencies, running the script will begin hiding root traces. The script will automatically download and configure the <span style="color: #0080FF;">TrickyStore</span> and <span style="color: #0080FF;">Zygisk-Next</span> modules as well as other modules without manual intervention.

## Contribution Guide

If you find any issues or have suggestions for improvement, feel free to submit them through GitHub's Issue or Pull Request features.

## Maintainers

Maintainer for versions 0.1-1.92 - RE2024
Maintainer for versions 1.9 and onwards - RDE

---

*Last Updated: 2024-10-27*
