# puppy-hydrometer

work in progress


## Remove Influxdb

apt-get purge --auto-remove influxdb2

rm -rf /etc/systemd/system/multi-user.target.wants/influxdb.service && rm -rf /etc/systemd/system/influxd.service && rm -rf /etc/default/influxdb2 && rm -rf /var/log/influxdb/ && rm -rf /etc/influxdb/ && rm -rf /var/lib/influxdb && rm -rf /usr/lib/systemd/system/influxdb.service && rm -rf /root/.influxdbv2/configs 

