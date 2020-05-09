## 打包镜像
```bash
tags=1.1.1
docker build -t cheungchan/google:$tags .
```
## 启动容器
```bash
tags=1.1.1
docker run -p 8003:80 -d cheungchan/google:$tags
```
# 修改替换字符
```bash
vim nginx/conf.d/google.conf
```
