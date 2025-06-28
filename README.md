# Docker快速入門

## 使用Docker的目的
對整個項目進行封裝，並上載到DockerHub等倉庫中，然後在其他設備上只要將鏡像下載下來，便能輕易運行並部署，這樣做的好處便是避免了使用者出現環境兼容問題，而且大大節省了重新部署的時間。

## 安裝Docker
前往[docker官網](https://www.docker.com/)進行下載安裝

![](images/docker_index.png)


## 創建並運行你的第一個docker容器
```
# 創建並運行名為my_docker的容器container
# -d 表示後台運行 --name 表示容器的名稱 nginx:alpine 表示基于alpine用dockerfile創建的nginx鏡像 可以把它理解為設置web server
docker run -d --name my_docker nginx:alpine
```

## 
