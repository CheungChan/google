## 打包镜像
docker build -t cheungchan/google:1.0 .
## 启动容器
docker run -p 8003:80 -d cheungchan/google:1.0
# 修改替换字符
vim nginx/conf.d/google.conf
