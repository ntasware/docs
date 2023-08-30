# All-in-One 快速部署

## 简介

ntas All-in-One快速部署支持部署在ubuntu 22.04.3操作系统上，通过一键安装、一键启动即可快速部署一套ntas。

## 准备工作

### 硬件需求

| <div style="width:200px;text-align:center">需求</div> | <div style="width:500px;text-align:center">参数</div> |
| :--: | :------------ |
| 内存 |      32G      |
| CPU  | 16核，支持AVX |
| 磁盘 | 320G |



### 软件要求

- ubuntu 22.04.3

## 部署

### 安装步骤

```shell
sudo su
tar xzvf ntasware-xxx.tar.gz
cd ntasware
./setup.sh
```



### 启动NTAS

```shell
sudo su
cd /higinet
./start-all.sh
```



### 停止NTAS

```shell
sudo su
cd /higinet
./stop-all.sh
```



## 访问web

使用浏览器访问：https://ip

