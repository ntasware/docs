# All-in-One 快速部署

## 1. 准备工作

### 硬件需求

- 内存 32G
- CPU 16核，支持AVX
- 硬盘 /higinet 320G

### 软件要求

- ubuntu 22.04.3

## 2.部署

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



## 3.访问web

https://ip:8080
