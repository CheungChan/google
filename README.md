## 打包镜像
tags=1.1
docker build -t cheungchan/google:$tags .
## 启动容器
tags=1.1
docker run -p 8003:80 -d cheungchan/google:$tags
# 修改替换字符
vim nginx/conf.d/google.conf
