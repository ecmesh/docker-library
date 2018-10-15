
docker pull registry.cn-beijing.aliyuncs.com/ecmesh/elasticsearch-oss:6.2.4
docker tag  registry.cn-beijing.aliyuncs.com/ecmesh/elasticsearch-oss:6.2.4  docker.elastic.co/elasticsearch/elasticsearch-oss:6.2.4
docker rmi  registry.cn-beijing.aliyuncs.com/ecmesh/elasticsearch-oss:6.2.4

docker pull registry.cn-beijing.aliyuncs.com/ecmesh/kibana-oss:6.2.4
docker tag  registry.cn-beijing.aliyuncs.com/ecmesh/kibana-oss:6.2.4  docker.elastic.co/kibana/kibana-oss:6.2.4
docker rmi  registry.cn-beijing.aliyuncs.com/ecmesh/kibana-oss:6.2.4

