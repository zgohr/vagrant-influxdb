# InfluxDB pre-0.9.0 Vagrant, Ansible, CentOS
Get the [InfluxDB](http://influxdb.com/) pre-0.9.0 HEAD running on a Vagrant box.

## Protips

* The playbook installs [Golang 1.4.1](https://golang.org/)
* It does not build or run the daemon, that is left for the end user
* There are multiple places the playbooks can have some variables abstracted. Right now they're pretty well coupled.

