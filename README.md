# info
based off https://github.com/hopsoft/docker-graphite-statsd

# command
docker run -d --name graphite -p 80:80 -p 2003:2003 -p 8125:8125/udp graphite/graphite

