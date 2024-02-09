---
slug: "./get-started"
title: "⚒️ Get Started"
sidebar_position: 2
---
# 快速入门

跟随本教程，十分钟（不包括下载耗时）开启您的第一个PowerNukkitX服务器。  
本教程将带您使用PowerNukkitX的命令行工具（CLI）来快速安装并启动服务器。

:::note
如果您使用的是Legacy版本的PNX，请查阅我们的开发文档更新至2.0
:::

## 下载命令行工具

点击前往 [Github发行版](https://github.com/PowerNukkitX/PNX-CLI/releases) 下载命令行。  
请根据您的计算机实际情况来下载对应的版本：

| 操作系统    | CPU          | 名称                  | 备注            |
|---------|--------------|---------------------|---------------|
| Windows | x86(x64)     | PNX-CLI-Windows-x86 ||
| Linux   | x86(x64)     | PNX-CLI-Linux-x86   ||
| Linux   | arm(aarch64) | PNX-CLI-Linux-arm   ||
| 其他平台    | 任意           | PNX-CLI-Jar         | 需要安装了Java才能使用 |

下载完成后，请解压并将其中的可执行文件提取出来

## 安装命令行工具  

下载完成后，请解压并将其中的可执行文件提取到一个文件夹中，PNX-CLI就安装完成了。  

请注意，路径中**不能带有空格**！否则CLI无法正常配置PNX环境。

## 启动PNX服务器

### Windows  

1. 双击运行`pnx.exe`
2. 接下来会询问你要使用哪个版本的核心，输入`1`并回车使用最新版本
3. 接下来会问你是否补全依赖库，输入`1`并回车选择`true`选项即可
4. 接下来会询问你使用的语言，输入`chs`选择中文（简体）即可
5. 你的PNX服务器已经成功启动，接下来你可以进一步配置服务器或者输入`stop`停止服务器
6. 记得，输入`stop`之后还需要在停服之后10秒内按下回车，否则会自动重启

### Linux  

1. 打开终端，输入`./pnx`并回车
2. 接下来会询问你要使用哪个版本的核心，输入`1`并回车使用最新版本
3. 接下来会问你是否补全依赖库，输入`1`并回车选择`true`选项即可
4. 接下来会询问你使用的语言，输入`chs`选择中文（简体）即可
5. 你的PNX服务器已经成功启动，接下来你可以进一步配置服务器或者输入`stop`停止服务器
6. 记得，输入`stop`之后还需要在停服之后10秒内按下回车，否则会自动重启

## 命令行工具高级用法

- 参阅[PNX-CLI启动器新手教学](./faq/PNX-CLI)  

## 配置您的PNX服务器  

- 参阅[Server.properties配置介绍](./config/server.properties)
- 参阅[Nukkit.yml配置介绍](./config/nukkit.yml)