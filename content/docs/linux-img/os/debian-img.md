---
title: Debian 镜像下载
weight: 2
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Debian 镜像下载地址

> Debian 镜像下载地址

官网地址 - [https://www.debian.org/](https://www.debian.org/)

## Debian 服务器版镜像 下载

Debian 镜像的安装同其他 Linux 发行版没有太大的差异，但 Debian 镜像的选择却十分考验耐心。日常使用最适合的是 包含非自由软件（含常见设备驱动）的 live CD 版本。

选择起来有困扰的话，不妨试试 ustc 的小工具

打开 [https://mirrors.ustc.edu.cn/](https://mirrors.ustc.edu.cn/)

选择 `获取发行版映像` 一栏的 `获取安装镜像` 按钮

![WX20221118-144911-2022-11-18-14-49-24](https://raw.githubusercontent.com/stuarthua/PicGo/master/linux-mind/WX20221118-144911-2022-11-18-14-49-24.png)

## Debian Cloud Image 下载

官网 - [https://cloud.debian.org/images/cloud/](https://cloud.debian.org/images/cloud/)

qcow2 和 raw，两种格式，视机器存储情况而定。

* Debian 11 qcow2 [https://cloud.debian.org/images/cloud/bullseye/latest/debian-11-generic-amd64.qcow2](https://cloud.debian.org/images/cloud/bullseye/latest/debian-11-generic-amd64.qcow2)
* Debian 10 qcow2 [https://cloud.debian.org/images/cloud/buster/latest/debian-10-generic-amd64.qcow2](https://cloud.debian.org/images/cloud/buster/latest/debian-10-generic-amd64.qcow2)

在众多镜像中，只需要关注几种 OpenStack、generic、genericcloud、nocloud。

* OpenStack: 多平台通用镜像
* generic：应该在任何使用 cloud-init 的环境中运行，例如 OpenStack、DigitalOcean 和裸机。
* genericcloud：类似于通用。应该在任何虚拟化环境中运行。通过排除物理硬件的驱动程序而小于“通用”。
* nocloud：主要用于测试构建过程本身。没有安装 cloud-init，允许没有密码的 root 登录。

一般，选择 generic 比较保底。
