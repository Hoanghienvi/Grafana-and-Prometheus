# Grafana-and-Prometheus


# Install Grafana-and-Prometheus
```
apt update
apt upgrade -y
wget https://github.com/Hoanghienvi/Grafana-and-Prometheus/blob/main/monitoring.sh
chmod +x monitoring.sh
./monitoring.sh deploy grafana
./monitoring.sh deploy Prometheus
```

# Star Services
```
systemctl start grafana-server prometheus
systemctl stop grafana-server prometheus
systemctl status grafana-server prometheus
systemctl restart grafana-server prometheus

```
