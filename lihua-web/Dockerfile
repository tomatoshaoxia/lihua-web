# 1. 基础镜像：拿官方 nginx 轻量系统当容器环境
FROM nginx:alpine

# 2. 把本地 index.html，复制到容器里 Nginx 网页根目录
COPY index.html /usr/share/nginx/html/index.html

# 3. 声明容器内部使用 80 端口（只是声明，方便看）
EXPOSE 80

# 4. 容器一启动，就运行 Nginx 服务
CMD ["nginx", "-g", "daemon off;"]
