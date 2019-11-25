# Telegraf InfluxDB Grafana Stack

 

## What if I don't want to use Rancher?


Install vagrant and Virtualbox
```bash
$ git clone https://github.com/matisku/tig-stack.git
$ cd tig-stack
$ docker-compose -f docker-compose-noplugins.yml up -d
```

Clone Repository
```bash
git clone https://github.com/adisaputra10/jmeter_grafana.git && cd jmeter_grafana
```

Running Vagrant
```bash
vagrant up
vagrant ssh
```

Running Docker
```bash
sudo su && cd /vagrant/jmeter_grafana
wait 10 minutes
username grafana : admin
password grafana : admin
```

Import  / openJMX to jmeter in folder jmeter in folder jmeter



