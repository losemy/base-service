
# 单机版es 安装
docker run -d \
--name es -p 9200:9200 \
-e "discovery.type=single-node" \ 
docker.elastic.co/elasticsearch/elasticsearch:6.3.2

