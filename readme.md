echo "vm.max_map_count=262144" >> /etc/sysctl.conf
systcl -p


docker-compose restart filebeat

Stack Management --> Index patterns

create index pattern --> name: nginx-* --> time field: @timestamp

