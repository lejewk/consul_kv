FROM lejewk/centos_redis_consul:latest

RUN mkdir -p /etc/consul.d
ADD /add /etc/consul.d

CMD consul agent -enable-script-checks -config-dir=/etc/consul.d/