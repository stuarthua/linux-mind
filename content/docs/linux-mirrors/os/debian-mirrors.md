---
title: Debian 镜像源
weight: 2
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Debian 镜像源

> Debian 镜像源

## 阿里云

官网文档 - [https://developer.aliyun.com/mirror/debian/](https://developer.aliyun.com/mirror/debian/)

{{< tabs "aliyun" >}}

{{< tab "11.x(bullseye)" >}}
## Debian 11.x Bullseye
> Bullseye -- 靶心🎯

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.aliyun.com/debian/ bullseye main non-free contrib
deb-src https://mirrors.aliyun.com/debian/ bullseye main non-free contrib
deb https://mirrors.aliyun.com/debian-security/ bullseye-security main
deb-src https://mirrors.aliyun.com/debian-security/ bullseye-security main
deb https://mirrors.aliyun.com/debian/ bullseye-updates main non-free contrib
deb-src https://mirrors.aliyun.com/debian/ bullseye-updates main non-free contrib
deb https://mirrors.aliyun.com/debian/ bullseye-backports main non-free contrib
deb-src https://mirrors.aliyun.com/debian/ bullseye-backports main non-free contrib
EOF"
```
{{< /tab >}}

{{< tab "10.x(buster)" >}}
## Debian 10.x Buster
> Buster -- 小屁孩

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.aliyun.com/debian/ buster main non-free contrib
deb-src https://mirrors.aliyun.com/debian/ buster main non-free contrib
deb https://mirrors.aliyun.com/debian-security buster/updates main
deb-src https://mirrors.aliyun.com/debian-security buster/updates main
deb https://mirrors.aliyun.com/debian/ buster-updates main non-free contrib
deb-src https://mirrors.aliyun.com/debian/ buster-updates main non-free contrib
deb https://mirrors.aliyun.com/debian/ buster-backports main non-free contrib
deb-src https://mirrors.aliyun.com/debian/ buster-backports main non-free contrib
EOF"
```
{{< /tab >}}

{{< tab "9.x(stretch)" >}}
## Debian 9.x Stretch
> Stretch -- 伸展

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.aliyun.com/debian/ stretch main non-free contrib
deb-src https://mirrors.aliyun.com/debian/ stretch main non-free contrib
deb https://mirrors.aliyun.com/debian-security stretch/updates main
deb-src https://mirrors.aliyun.com/debian-security stretch/updates main
deb https://mirrors.aliyun.com/debian/ stretch-updates main non-free contrib
deb-src https://mirrors.aliyun.com/debian/ stretch-updates main non-free contrib
#deb https://mirrors.aliyun.com/debian/ stretch-backports main non-free contrib
#deb-src https://mirrors.aliyun.com/debian/ stretch-backports main non-free contrib
EOF"
```
{{< /tab >}}

{{< /tabs >}}


## 腾讯云

官网文档 - [https://mirrors.tencent.com/help/debian.html](https://mirrors.tencent.com/help/debian.html)

{{< tabs "tencent" >}}

{{< tab "11.x(bullseye)" >}}
## Debian 11.x Bullseye
> Bullseye -- 靶心🎯

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.cloud.tencent.com/debian/ bullseye main contrib non-free
deb https://mirrors.cloud.tencent.com/debian/ bullseye-updates main contrib non-free
deb https://mirrors.cloud.tencent.com/debian/ bullseye-backports main contrib non-free
deb https://mirrors.cloud.tencent.com/debian-security bullseye/updates main contrib non-free
deb-src https://mirrors.cloud.tencent.com/debian/ bullseye main contrib non-free
deb-src https://mirrors.cloud.tencent.com/debian/ bullseye-updates main contrib non-free
deb-src https://mirrors.cloud.tencent.com/debian/ bullseye-backports main contrib non-free
deb-src https://mirrors.cloud.tencent.com/debian-security bullseye/updates main contrib non-free
EOF"
```
{{< /tab >}}

{{< tab "10.x(buster)" >}}
## Debian 10.x Buster
> Buster -- 小屁孩

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.cloud.tencent.com/debian/ buster main contrib non-free
deb https://mirrors.cloud.tencent.com/debian/ buster-updates main contrib non-free
deb https://mirrors.cloud.tencent.com/debian/ buster-backports main contrib non-free
deb https://mirrors.cloud.tencent.com/debian-security buster/updates main contrib non-free
deb-src https://mirrors.cloud.tencent.com/debian/ buster main contrib non-free
deb-src https://mirrors.cloud.tencent.com/debian/ buster-updates main contrib non-free
deb-src https://mirrors.cloud.tencent.com/debian/ buster-backports main contrib non-free
deb-src https://mirrors.cloud.tencent.com/debian-security buster/updates main contrib non-free
EOF"
```
{{< /tab >}}

{{< tab "9.x(stretch)" >}}
## Debian 9.x Stretch
> Stretch -- 伸展

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb http://mirrors.cloud.tencent.com/debian stretch main contrib non-free
deb http://mirrors.cloud.tencent.com/debian stretch-updates main contrib non-free
#deb http://mirrors.cloud.tencent.com/debian stretch-backports main contrib non-free
#deb http://mirrors.cloud.tencent.com/debian stretch-proposed-updates main contrib non-free
deb-src http://mirrors.cloud.tencent.com/debian stretch main contrib non-free
deb-src http://mirrors.cloud.tencent.com/debian stretch-updates main contrib non-free
#deb-src http://mirrors.cloud.tencent.com/debian stretch-backports main contrib non-free
#deb-src http://mirrors.cloud.tencent.com/debian stretch-proposed-updates main contrib non-free
EOF"
```
{{< /tab >}}

{{< /tabs >}}


## 网易云

官网文档 - [https://mirrors.163.com/.help/debian.html](https://mirrors.163.com/.help/debian.html)

{{< tabs "163" >}}

{{< tab "11.x(bullseye)" >}}
## Debian 11.x Bullseye
> Bullseye -- 靶心🎯

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb http://mirrors.163.com/debian/ bullseye main non-free contrib
deb http://mirrors.163.com/debian/ bullseye-updates main non-free contrib
deb http://mirrors.163.com/debian/ bullseye-backports main non-free contrib
deb-src http://mirrors.163.com/debian/ bullseye main non-free contrib
deb-src http://mirrors.163.com/debian/ bullseye-updates main non-free contrib
deb-src http://mirrors.163.com/debian/ bullseye-backports main non-free contrib
deb http://mirrors.163.com/debian-security/ bullseye/updates main non-free contrib
deb-src http://mirrors.163.com/debian-security/ bullseye/updates main non-free contrib
EOF"
```
{{< /tab >}}

{{< tab "10.x(buster)" >}}
## Debian 10.x Buster
> Buster -- 小屁孩

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb http://mirrors.163.com/debian/ buster main non-free contrib
deb http://mirrors.163.com/debian/ buster-updates main non-free contrib
deb http://mirrors.163.com/debian/ buster-backports main non-free contrib
deb-src http://mirrors.163.com/debian/ buster main non-free contrib
deb-src http://mirrors.163.com/debian/ buster-updates main non-free contrib
deb-src http://mirrors.163.com/debian/ buster-backports main non-free contrib
deb http://mirrors.163.com/debian-security/ buster/updates main non-free contrib
deb-src http://mirrors.163.com/debian-security/ buster/updates main non-free contrib
EOF"
```
{{< /tab >}}

{{< tab "9.x(stretch)" >}}
## Debian 9.x Stretch
> Stretch -- 伸展

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb http://mirrors.163.com/debian/ stretch main non-free contrib
deb http://mirrors.163.com/debian/ stretch-updates main non-free contrib
deb http://mirrors.163.com/debian/ stretch-backports main non-free contrib
deb-src http://mirrors.163.com/debian/ stretch main non-free contrib
deb-src http://mirrors.163.com/debian/ stretch-updates main non-free contrib
deb-src http://mirrors.163.com/debian/ stretch-backports main non-free contrib
deb http://mirrors.163.com/debian-security/ stretch/updates main non-free contrib
deb-src http://mirrors.163.com/debian-security/ stretch/updates main non-free contrib
EOF"
```
{{< /tab >}}

{{< /tabs >}}


## 清华

官网文档 - [https://mirrors.tuna.tsinghua.edu.cn/help/debian/](https://mirrors.tuna.tsinghua.edu.cn/help/debian/)

{{< tabs "tuna" >}}

{{< tab "11.x(bullseye)" >}}
## Debian 11.x Bullseye
> Bullseye -- 靶心🎯

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
# 默认注释了源码镜像以提高 apt update 速度，如有需要可自行取消注释
deb https://mirrors.tuna.tsinghua.edu.cn/debian/ bullseye main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian/ bullseye main contrib non-free
deb https://mirrors.tuna.tsinghua.edu.cn/debian/ bullseye-updates main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian/ bullseye-updates main contrib non-free

deb https://mirrors.tuna.tsinghua.edu.cn/debian/ bullseye-backports main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian/ bullseye-backports main contrib non-free

deb https://mirrors.tuna.tsinghua.edu.cn/debian-security bullseye-security main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian-security bullseye-security main contrib non-free
EOF"
```
{{< /tab >}}

{{< tab "10.x(buster)" >}}
## Debian 10.x Buster
> Buster -- 小屁孩

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
# 默认注释了源码镜像以提高 apt update 速度，如有需要可自行取消注释
deb https://mirrors.tuna.tsinghua.edu.cn/debian/ buster main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian/ buster main contrib non-free
deb https://mirrors.tuna.tsinghua.edu.cn/debian/ buster-updates main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian/ buster-updates main contrib non-free

deb https://mirrors.tuna.tsinghua.edu.cn/debian/ buster-backports main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian/ buster-backports main contrib non-free

deb https://mirrors.tuna.tsinghua.edu.cn/debian-security buster/updates main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian-security buster/updates main contrib non-free
EOF"
```
{{< /tab >}}

{{< tab "9.x(stretch)" >}}
## Debian 9.x Stretch
> Stretch -- 伸展

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
# 默认注释了源码镜像以提高 apt update 速度，如有需要可自行取消注释
deb https://mirrors.tuna.tsinghua.edu.cn/debian/ stretch main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian/ stretch main contrib non-free
deb https://mirrors.tuna.tsinghua.edu.cn/debian/ stretch-updates main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian/ stretch-updates main contrib non-free

deb https://mirrors.tuna.tsinghua.edu.cn/debian/ stretch-backports main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian/ stretch-backports main contrib non-free

deb https://mirrors.tuna.tsinghua.edu.cn/debian-security stretch/updates main contrib non-free
# deb-src https://mirrors.tuna.tsinghua.edu.cn/debian-security stretch/updates main contrib non-free
EOF"
```
{{< /tab >}}

{{< /tabs >}}

## 中科大

官网文档 - [https://mirrors.ustc.edu.cn/help/debian.html](https://mirrors.ustc.edu.cn/help/debian.html)

> 推荐小工具 - [https://mirrors.ustc.edu.cn/repogen/](https://mirrors.ustc.edu.cn/repogen/)

{{< tabs "ustc" >}}

{{< tab "11.x(bullseye)" >}}
## Debian 11.x Bullseye
> Bullseye -- 靶心🎯

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.ustc.edu.cn/debian/ bullseye main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian/ bullseye main contrib non-free

deb https://mirrors.ustc.edu.cn/debian/ bullseye-updates main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian/ bullseye-updates main contrib non-free

deb https://mirrors.ustc.edu.cn/debian/ bullseye-backports main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian/ bullseye-backports main contrib non-free

deb https://mirrors.ustc.edu.cn/debian-security/ bullseye-security main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian-security/ bullseye-security main contrib non-free
EOF"
```
{{< /tab >}}

{{< tab "10.x(buster)" >}}
## Debian 10.x Buster
> Buster -- 小屁孩

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.ustc.edu.cn/debian/ buster main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian/ buster main contrib non-free

deb https://mirrors.ustc.edu.cn/debian/ buster-updates main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian/ buster-updates main contrib non-free

deb https://mirrors.ustc.edu.cn/debian/ buster-backports main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian/ buster-backports main contrib non-free

deb https://mirrors.ustc.edu.cn/debian-security/ buster/updates main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian-security/ buster/updates main contrib non-free
EOF"
```
{{< /tab >}}

{{< tab "9.x(stretch)" >}}
## Debian 9.x Stretch
> Stretch -- 伸展

复制以下命令

```bash
sudo bash -c "cat << EOF > /etc/apt/sources.list && apt update 
deb https://mirrors.ustc.edu.cn/debian/ stretch main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian/ stretch main contrib non-free

deb https://mirrors.ustc.edu.cn/debian/ stretch-updates main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian/ stretch-updates main contrib non-free

deb https://mirrors.ustc.edu.cn/debian/ stretch-backports main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian/ stretch-backports main contrib non-free

deb https://mirrors.ustc.edu.cn/debian-security/ stretch/updates main contrib non-free
deb-src https://mirrors.ustc.edu.cn/debian-security/ stretch/updates main contrib non-free
EOF"
```
{{< /tab >}}

{{< /tabs >}}
