---
title: Ubuntu 镜像源
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Ubuntu 镜像源

> Ubuntu 镜像源

## 阿里云

官网文档 - [https://developer.aliyun.com/mirror/ubuntu/](https://developer.aliyun.com/mirror/ubuntu/)

{{< tabs "aliyun" >}}

{{< tab "22.04 LTS" >}}
## Ubuntu 22.04 LTS Jammy
> Jammy Jellyfish -- 适意的水母

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.aliyun.com/ubuntu/ jammy main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ jammy main restricted universe multiverse
deb https://mirrors.aliyun.com/ubuntu/ jammy-updates main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ jammy-updates main restricted universe multiverse
deb https://mirrors.aliyun.com/ubuntu/ jammy-backports main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ jammy-backports main restricted universe multiverse
deb https://mirrors.aliyun.com/ubuntu/ jammy-security main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ jammy-security main restricted universe multiverse

# deb https://mirrors.aliyun.com/ubuntu/ jammy-proposed main restricted universe multiverse
# deb-src https://mirrors.aliyun.com/ubuntu/ jammy-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "20.04 LTS" >}}
## Ubuntu 20.04 LTS Focal
> Focal Fossa -- 焦点的马岛长尾狸猫

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ focal main restricted universe multiverse
deb https://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ focal-updates main restricted universe multiverse
deb https://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ focal-backports main restricted universe multiverse
deb https://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ focal-security main restricted universe multiverse

# deb https://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse
# deb-src https://mirrors.aliyun.com/ubuntu/ focal-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "18.04 LTS" >}}
## Ubuntu 18.04 LTS Bionic
> Bionic Beaver -- 仿生的河狸

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.aliyun.com/ubuntu/ bionic main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ bionic main restricted universe multiverse
deb https://mirrors.aliyun.com/ubuntu/ bionic-updates main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ bionic-updates main restricted universe multiverse
deb https://mirrors.aliyun.com/ubuntu/ bionic-backports main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ bionic-backports main restricted universe multiverse
deb https://mirrors.aliyun.com/ubuntu/ bionic-security main restricted universe multiverse
deb-src https://mirrors.aliyun.com/ubuntu/ bionic-security main restricted universe multiverse

# deb https://mirrors.aliyun.com/ubuntu/ bionic-proposed main restricted universe multiverse
# deb-src https://mirrors.aliyun.com/ubuntu/ bionic-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< /tabs >}}


## 腾讯云

官网文档 - [https://mirrors.tencent.com/help/ubuntu.html](https://mirrors.tencent.com/help/ubuntu.html)

{{< tabs "tencent" >}}

{{< tab "22.04 LTS" >}}
## Ubuntu 22.04 LTS Jammy
> Jammy Jellyfish -- 适意的水母

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.cloud.tencent.com/ubuntu/ jammy main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ jammy main restricted universe multiverse
deb https://mirrors.cloud.tencent.com/ubuntu/ jammy-updates main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ jammy-updates main restricted universe multiverse
deb https://mirrors.cloud.tencent.com/ubuntu/ jammy-backports main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ jammy-backports main restricted universe multiverse
deb https://mirrors.cloud.tencent.com/ubuntu/ jammy-security main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ jammy-security main restricted universe multiverse

# deb https://mirrors.cloud.tencent.com/ubuntu/ jammy-proposed main restricted universe multiverse
# deb-src https://mirrors.cloud.tencent.com/ubuntu/ jammy-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "20.04 LTS" >}}
## Ubuntu 20.04 LTS Focal
> Focal Fossa -- 焦点的马岛长尾狸猫

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.cloud.tencent.com/ubuntu/ focal main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ focal main restricted universe multiverse
deb https://mirrors.cloud.tencent.com/ubuntu/ focal-updates main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ focal-updates main restricted universe multiverse
deb https://mirrors.cloud.tencent.com/ubuntu/ focal-backports main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ focal-backports main restricted universe multiverse
deb https://mirrors.cloud.tencent.com/ubuntu/ focal-security main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ focal-security main restricted universe multiverse

# deb https://mirrors.cloud.tencent.com/ubuntu/ focal-proposed main restricted universe multiverse
# deb-src https://mirrors.cloud.tencent.com/ubuntu/ focal-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "18.04 LTS" >}}
## Ubuntu 18.04 LTS Bionic
> Bionic Beaver -- 仿生的河狸

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.cloud.tencent.com/ubuntu/ bionic main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ bionic main restricted universe multiverse
deb https://mirrors.cloud.tencent.com/ubuntu/ bionic-updates main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ bionic-updates main restricted universe multiverse
deb https://mirrors.cloud.tencent.com/ubuntu/ bionic-backports main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ bionic-backports main restricted universe multiverse
deb https://mirrors.cloud.tencent.com/ubuntu/ bionic-security main restricted universe multiverse
deb-src https://mirrors.cloud.tencent.com/ubuntu/ bionic-security main restricted universe multiverse

# deb https://mirrors.cloud.tencent.com/ubuntu/ bionic-proposed main restricted universe multiverse
# deb-src https://mirrors.cloud.tencent.com/ubuntu/ bionic-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< /tabs >}}


## 网易云

官网文档 - [https://mirrors.163.com/.help/ubuntu.html](https://mirrors.163.com/.help/ubuntu.html)

{{< tabs "163" >}}

{{< tab "22.04 LTS" >}}
## Ubuntu 22.04 LTS Jammy
> Jammy Jellyfish -- 适意的水母

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.163.com/ubuntu/ jammy main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ jammy main restricted universe multiverse
deb https://mirrors.163.com/ubuntu/ jammy-updates main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ jammy-updates main restricted universe multiverse
deb https://mirrors.163.com/ubuntu/ jammy-backports main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ jammy-backports main restricted universe multiverse
deb https://mirrors.163.com/ubuntu/ jammy-security main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ jammy-security main restricted universe multiverse

# deb https://mirrors.163.com/ubuntu/ jammy-proposed main restricted universe multiverse
# deb-src https://mirrors.163.com/ubuntu/ jammy-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "20.04 LTS" >}}
## Ubuntu 20.04 LTS Focal
> Focal Fossa -- 焦点的马岛长尾狸猫

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.163.com/ubuntu/ focal main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ focal main restricted universe multiverse
deb https://mirrors.163.com/ubuntu/ focal-updates main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ focal-updates main restricted universe multiverse
deb https://mirrors.163.com/ubuntu/ focal-backports main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ focal-backports main restricted universe multiverse
deb https://mirrors.163.com/ubuntu/ focal-security main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ focal-security main restricted universe multiverse

# deb https://mirrors.163.com/ubuntu/ focal-proposed main restricted universe multiverse
# deb-src https://mirrors.163.com/ubuntu/ focal-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "18.04 LTS" >}}
## Ubuntu 18.04 LTS Bionic
> Bionic Beaver -- 仿生的河狸

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.163.com/ubuntu/ bionic main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ bionic main restricted universe multiverse
deb https://mirrors.163.com/ubuntu/ bionic-updates main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ bionic-updates main restricted universe multiverse
deb https://mirrors.163.com/ubuntu/ bionic-backports main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ bionic-backports main restricted universe multiverse
deb https://mirrors.163.com/ubuntu/ bionic-security main restricted universe multiverse
deb-src https://mirrors.163.com/ubuntu/ bionic-security main restricted universe multiverse

# deb https://mirrors.163.com/ubuntu/ bionic-proposed main restricted universe multiverse
# deb-src https://mirrors.163.com/ubuntu/ bionic-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< /tabs >}}


## 清华

官网文档 - [https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/](https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/)

{{< tabs "tuna" >}}

{{< tab "22.04 LTS" >}}
## Ubuntu 22.04 LTS Jammy
> Jammy Jellyfish -- 适意的水母

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
# 建议默认情况下，注释源码镜像以提高 apt update 速度，如需自行编译相关软件可取消注释
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy main restricted universe multiverse
#deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy-updates main restricted universe multiverse
#deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy-updates main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy-backports main restricted universe multiverse
#deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy-backports main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy-security main restricted universe multiverse
#deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy-security main restricted universe multiverse

# 预发布软件源，不建议启用
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy-proposed main restricted universe multiverse
deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ jammy-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "20.04 LTS" >}}
## Ubuntu 20.04 LTS Focal
> Focal Fossa -- 焦点的马岛长尾狸猫

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
# 默认注释了源码镜像以提高 apt update 速度，如需自行编译相关软件可取消注释
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-security main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-security main restricted universe multiverse

# 预发布软件源，不建议启用
# deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "18.04 LTS" >}}
## Ubuntu 18.04 LTS Bionic
> Bionic Beaver -- 仿生的河狸

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
# 默认注释了源码镜像以提高 apt update 速度，如需自行编译相关软件可取消注释
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic-updates main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic-updates main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic-backports main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic-backports main restricted universe multiverse
deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic-security main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic-security main restricted universe multiverse

# 预发布软件源，不建议启用
# deb https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic-proposed main restricted universe multiverse
# deb-src https://mirrors.tuna.tsinghua.edu.cn/ubuntu/ bionic-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< /tabs >}}


## 中科大

官网文档 - [https://mirrors.ustc.edu.cn/help/ubuntu.html](https://mirrors.ustc.edu.cn/help/ubuntu.html)

> 推荐小工具 - [https://mirrors.ustc.edu.cn/repogen/](https://mirrors.ustc.edu.cn/repogen/)

{{< tabs "ustc" >}}

{{< tab "22.04 LTS" >}}
## Ubuntu 22.04 LTS Jammy
> Jammy Jellyfish -- 适意的水母

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
# 建议默认情况下，注释源码镜像以提高 apt update 速度，如需自行编译相关软件可取消注释
deb https://mirrors.ustc.edu.cn/ubuntu/ jammy main restricted universe multiverse
#deb-src https://mirrors.ustc.edu.cn/ubuntu/ jammy main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ jammy-updates main restricted universe multiverse
#deb-src https://mirrors.ustc.edu.cn/ubuntu/ jammy-updates main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ jammy-backports main restricted universe multiverse
#deb-src https://mirrors.ustc.edu.cn/ubuntu/ jammy-backports main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ jammy-security main restricted universe multiverse
#deb-src https://mirrors.ustc.edu.cn/ubuntu/ jammy-security main restricted universe multiverse

# 预发布软件源，不建议启用
deb https://mirrors.ustc.edu.cn/ubuntu/ jammy-proposed main restricted universe multiverse
deb-src https://mirrors.ustc.edu.cn/ubuntu/ jammy-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "20.04 LTS" >}}
## Ubuntu 20.04 LTS Focal
> Focal Fossa -- 焦点的马岛长尾狸猫

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
# 默认注释了源码镜像以提高 apt update 速度，如需自行编译相关软件可取消注释
deb https://mirrors.ustc.edu.cn/ubuntu/ focal main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ focal-security main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal-security main restricted universe multiverse

# 预发布软件源，不建议启用
# deb https://mirrors.ustc.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ focal-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< tab "18.04 LTS" >}}
## Ubuntu 18.04 LTS Bionic
> Bionic Beaver -- 仿生的河狸

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
# 默认注释了源码镜像以提高 apt update 速度，如需自行编译相关软件可取消注释
deb https://mirrors.ustc.edu.cn/ubuntu/ bionic main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ bionic-updates main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic-updates main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ bionic-backports main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic-backports main restricted universe multiverse
deb https://mirrors.ustc.edu.cn/ubuntu/ bionic-security main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic-security main restricted universe multiverse

# 预发布软件源，不建议启用
# deb https://mirrors.ustc.edu.cn/ubuntu/ bionic-proposed main restricted universe multiverse
# deb-src https://mirrors.ustc.edu.cn/ubuntu/ bionic-proposed main restricted universe multiverse
EOF"
```
{{< /tab >}}

{{< /tabs >}}