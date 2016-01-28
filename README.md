# core
docker run -it --net='host' -P -e IP=$(facter ipaddress_eth0) dtank/core

^^ copy discovery url/token into /usr/local/bin/run-etcd
