---
title: "常用国内镜像源"
weight: 1
bookFlatSection: true
---

## 常用国内镜像源

{{< hint info >}}
PS: 近期各家云的镜像站集体抽风，速度莫名其妙跑到了 10-500K，甚至还远不如各大高校提供的镜像站
{{< /hint >}}

* [阿里云 镜像站](https://developer.aliyun.com/mirror/)
* [腾讯云 镜像站](https://mirrors.cloud.tencent.com/)
* [网易云 镜像站](https://mirrors.163.com/)
* [华为 镜像站](https://mirrors.huaweicloud.com/home)
* [清华 - tuna 镜像站](https://mirrors.tuna.tsinghua.edu.cn/)
    - [https://opentuna.cn](https://opentuna.cn) - tuna 兄弟站，提供同样的内容，分流。用的人还比较少，速度蛮快的
* [中科大 - ustc 镜像站](https://mirrors.ustc.edu.cn/)
* 上海交通大学 - sjtu 镜像站。共设两台服务器 (思源 + 致远)，原镜像站 `ftp.sjtu.edu.cn` 还在维护。
    - [https://mirror.sjtu.edu.cn/](https://mirror.sjtu.edu.cn/) - 思源 (Siyuan) - 兼容原 sjtu 镜像站
    - [https://mirrors.sjtug.sjtu.edu.cn/](https://mirrors.sjtug.sjtu.edu.cn/) - 致远 (Zhiyuan) - 同步新镜像
    - [https://ftp.sjtu.edu.cn/](https://ftp.sjtu.edu.cn/) - 原 sjtu 镜像站

### 推荐

{{< hint info >}}
推荐:
* 镜像站的终点 Z，清华博士生的毕业项目
  - [官方 Github](https://github.com/mirrorz-org)
  - [https://mirrorz.org/](https://mirrorz.org/)
* 快点开源镜像搜索服务 - [https://mirrors.quickso.cn/](https://mirrors.quickso.cn/)
{{< /hint >}}

### 测速

```bash
# 请确保本机已经安装 python3
$ pip install requests

# 开始测试
$ curl https://mirrorz.org/oh-my-mirrorz.py | python3
...
...
RANK        ABBR              SPEED
00:         USTC              32.24 MiB/s
01:         SJTUG - Siyuan    28.09 MiB/s
02:         NJU               28.05 MiB/s
03:         SDU               26.95 MiB/s
04:         SCAU              24.41 MiB/s
05:         CQU               22.43 MiB/s
06:         PKU               21.94 MiB/s
07:         BFSU              21.93 MiB/s
08:         OpenTUNA          21.79 MiB/s
09:         SUSTech CRA       21.72 MiB/s
10:         BUPT              18.97 MiB/s
```

测速排名 (from 上海)

* [中科大 - ustc 镜像站](https://mirrors.ustc.edu.cn/)
* 上海交通大学 - sjtu 镜像站。共设两台服务器 (思源 + 致远)，原镜像站 `ftp.sjtu.edu.cn` 还在维护。
    - [https://mirror.sjtu.edu.cn/](https://mirror.sjtu.edu.cn/) - 思源 (Siyuan) - 兼容原 sjtu 镜像站
    - [https://mirrors.sjtug.sjtu.edu.cn/](https://mirrors.sjtug.sjtu.edu.cn/) - 致远 (Zhiyuan) - 同步新镜像
    - [https://ftp.sjtu.edu.cn/](https://ftp.sjtu.edu.cn/) - 原 sjtu 镜像站
* [南京大学 - nju 镜像站](https://mirrors.nju.edu.cn/)
* [山东大学 - sdu 镜像站](https://mirrors.sdu.edu.cn/#/mirror)
* [华南农业大学 - scau 镜像站](https://mirrors.scau.edu.cn/)
* [重庆大学 - cqu 镜像站](https://mirrors.cqu.edu.cn/)
* [北京大学 - pku 镜像站](https://mirrors.pku.edu.cn/Mirrors)
* [北京外国语大学 - bfsu 镜像站](https://mirrors.bfsu.edu.cn/)
* [清华 - opentuna 镜像站 (分流)](https://opentuna.cn)
* [南方科技大学 - sustech 镜像站](https://mirrors.sustech.edu.cn/)
* [北京邮电大学 - bupt 镜像站](https://mirrors.bupt.edu.cn/)