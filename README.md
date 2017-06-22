# Rancher Catalog ELK

Creates ELK v5.4.1 stacks in Rancher

### Scalable ELK Cluster v5.4.1

Has a complete ELK cluster, and a version that includes a [Rancher load balancer](elk-scalable-stack/1/)

  * [Cerebro](https://github.com/dm/docker-cerebro)
  * [Curator](https://github.com/sxmichael/curator-docker)
  * ElasticSearch Client
  * ElasticSearch Data
  * ElasticSearch load balancer [optional] (Expose Kibana and Cerebro)
  * ElasticSearch Master
  * Kibana
  * Logspout
  * Logstash
  * Logstash Collector
  * Logstash Indexer
  * Redis

### ELK v5.4.1

Development version (not scalable ElasticSearch)

  * [Cerebro](https://github.com/dm/docker-cerebro)
  * [Curator](https://github.com/sxmichael/curator-docker)
  * ElasticSearch (and data volume)
  * Kibana
  * Logspout
  * Logstash
  * Logstash Collector
  * Logstash Indexer
  * Redis

## License

Apache 2.0
