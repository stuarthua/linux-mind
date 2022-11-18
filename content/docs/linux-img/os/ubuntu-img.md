---
title: Ubuntu 镜像下载
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Ubuntu 镜像下载地址

> Ubuntu 镜像下载地址

## Ubuntu 服务器版镜像 下载

官网下载地址 - [https://cn.ubuntu.com/download/server/step1](https://cn.ubuntu.com/download/server/step1)

* 官网直接下载 [22.04 LTS](https://releases.ubuntu.com/22.04.1/ubuntu-22.04.1-live-server-amd64.iso)
* 官网直接下载 [20.04 LTS](https://releases.ubuntu.com/20.04/ubuntu-20.04.4-live-server-amd64.iso)

如果需要 BitTorrent 下载

* BT 下载 [22.04 LTS](https://releases.ubuntu.com/22.04/ubuntu-22.04.1-live-server-amd64.iso.torrent)
* BT 下载 [20.04 LTS](https://releases.ubuntu.com/20.04/ubuntu-20.04.4-live-server-amd64.iso.torrent)

选择起来有困扰的话，不妨试试 ustc 的小工具

打开 [https://mirrors.ustc.edu.cn/](https://mirrors.ustc.edu.cn/)

选择 `获取发行版映像` 一栏的 `获取安装镜像` 按钮

![WX20221118-144911-2022-11-18-14-49-24](https://raw.githubusercontent.com/stuarthua/PicGo/master/linux-mind/WX20221118-144911-2022-11-18-14-49-24.png)

## Ubuntu Cloud Image 下载

官网 - [https://cloud-images.ubuntu.com/](https://cloud-images.ubuntu.com/)

对于在 PVE 中使用的场景，建议下载 `.img` 后缀的文件，使用以下命令导入到虚拟机中

```bash
$ qm importdisk 104 ubuntu-20.04-server-cloudimg-amd64.img raid0 --format=qcow2

#: 104 为虚拟机的ID
#: raid0 为存储的名称，如果没有额外存储，则默认是 local
#: --format=qcow2 为转换后的格式
```
