# ARL(Asset Reconnaissance Lighthouse)资产侦察灯塔系统
[![Python 3.6](https://img.shields.io/badge/python-3.6-yellow.svg)](https://www.python.org/)
[![Docker Images](https://img.shields.io/docker/pulls/tophant/arl.svg)](https://hub.docker.com/r/tophant/arl)
[![Github Issues](https://img.shields.io/github/issues/TophantTechnology/ARL.svg)](https://github.com/TophantTechnology/ARL/issues)
[![Github Stars](https://img.shields.io/github/stars/TophantTechnology/ARL.svg)](https://github.com/TophantTechnology/ARL/stargazers)

## 1# 注明

- **因为灯塔ARL的官方开源项目被删除了，所以建立了本开源项目留作备份，本项目所有内容均来自于[TophantTechnology/ARL](https://github.com/TophantTechnology/ARL)最新版本**
- **ARL官方开源项目关闭的具体原因请看：[https://mp.weixin.qq.com/s/hM3t3lYQVqDOlrLKz3_TSQ](https://mp.weixin.qq.com/s/hM3t3lYQVqDOlrLKz3_TSQ)**
- **此仓库为原版ARL的docker备份，可直接使用原版方式搭建**


## # Docker 启动

```C
git clone https://github.com/Feng4/ARL-2.6.2.git

//进入项目文件夹
cd ARL-2.6.2/docker/

docker volume create --name=arl_db
docker-compose pull
docker-compose up -d

```




