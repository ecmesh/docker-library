
#elastic-stack相关images同步

```bash
docker.elastic.co/elasticsearch/elasticsearch-oss:6.4.0

docker.elastic.co/kibana/kibana-oss:6.4.0
docker.elastic.co/logstash/logstash-oss:6.2.2


```




#手工拉取镜像示例： 
```bash

docker pull registry.cn-beijing.aliyuncs.com/ecmesh/elasticsearch-oss:6.4.0
docker tag registry.cn-beijing.aliyuncs.com/ecmesh/elasticsearch-oss:6.4.0 docker.elastic.co/elasticsearch/elasticsearch-oss:6.4.0
docker rmi registry.cn-beijing.aliyuncs.com/ecmesh/elasticsearch-oss:6.4.0



docker pull registry.cn-beijing.aliyuncs.com/ecmesh/kibana-oss:6.4.0
docker tag registry.cn-beijing.aliyuncs.com/ecmesh/kibana/kibana-oss:6.4.0 docker.elastic.co/kibana/kibana-oss:6.4.0
docker rmi registry.cn-beijing.aliyuncs.com/ecmesh/kibana-oss:6.4.0


docker pull registry.cn-beijing.aliyuncs.com/ecmesh/logstash-oss:6.2.2
docker tag registry.cn-beijing.aliyuncs.com/ecmesh/logstash-oss:6.2.2 docker.elastic.co/logstash/logstash-oss:6.2.2
docker rmi registry.cn-beijing.aliyuncs.com/ecmesh/logstash-oss:6.2.2


```

