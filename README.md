# grafana-influxdb
Contains steps and configuration to setup Grafana Stack for Production Monitoring

<img src="tig-monitor-logic.png" height="300px" width="600px" />
Setup Grafana and influxdb


########### Steps for Grafana ############## <br/>
1> wget https://s3-us-west-2.amazonaws.com/grafana-releases/release/grafana-4.3.2.linux-x64.tar.gz<br/>
2> tar -xzf grafana-4.3.2.linux-x64.tar.gz<br/>
3> cd grafana-4.3.2<br/>
4> bin/grafana-server<br/>
<br/>

########### Steps for InfluxDb ###############<br/>
1> wget https://dl.influxdata.com/influxdb/releases/influxdb-1.2.4_linux_amd64.tar.gz<br/>
2> tar -xzf influxdb-1.2.4_linux_amd64.tar.gz<br/>
3> cd influxdb-1.2.4-1/<br/>

########### Installing Telegraf(collector) ############## <br/>
<i>Install using rpm</i>
&nbsp;<a href="https://repos.influxdata.com/centos/7Server/amd64/stable/">https://repos.influxdata.com/centos/7Server/amd64/stable/ (Influx and telegraf Rpm repo)</a><br/>


<i>Install using debian</i><br/>
1> wget https://dl.influxdata.com/telegraf/releases/telegraf_1.0.0_amd64.deb<br/>
2> sudo dpkg -i telegraf_1.0.0_amd64.deb<br/>
