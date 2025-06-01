# 使用官方 Ubuntu 基础镜像
FROM ubuntu:22.04

# 环境配置
ENV DEBIAN_FRONTEND=noninteractive

# 安装依赖（git, ruby, bundler, nodejs for jekyll, build tools）
RUN apt-get update && \
    apt-get install -y \
    git curl gnupg build-essential \
    ruby-full nodejs npm && \
    gem install bundler jekyll -v 3.9.0 && \
    apt-get clean

# 创建工作目录
WORKDIR /site

# 默认执行命令（可被 docker run 覆盖）
CMD ["jekyll", "serve", "--host", "0.0.0.0"]
