### Running logstash container

```bash
docker run --rm -it -p 544:544 -v /home/spalfreyman/dev/docker/logstash/pipeline/:/usr/share/logstash/pipeline/ docker.elastic.co/logstash/logstash:7.16.1
```

### Pipe events via netcat

`nc 127.0.0.1 544`
