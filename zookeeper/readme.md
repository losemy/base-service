

# docker 安装单机版zk
docker run -d \
-p 2181:2181 \
-v /docker/zookeeper/data/:/data/ \
--name=zk  \
--privileged zookeeper