# DockerFile学习

## 常用命令

命令 | 说明 
:-:|:--
FROM|基于哪个镜像来实现
MAINTAINER|镜像的创建者
ENV|环境变量
RUN|执行的命令
ADD|添加宿主机文件到容器里，有需要解压的文件会自动解压
COPY|添加宿主机文件到容器里
WORKDIR|工作目录
EXPOSE|容器内应用可以使用的端口
CMD|容器启动后执行的程序，如果执行 docker run 后面跟启动命令会被覆盖掉
ENTRYPOINT|与 CMD 功能相同，但需 docker run 不会覆盖，如果需要覆盖可增加参数 -entrypoint 来覆盖
VOLUMN|将宿主机的目录挂载到容器里

