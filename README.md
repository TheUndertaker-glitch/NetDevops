# NetDevops
Projet DevOps

## Architecture Réseau ERIS
- DMZ : 172.20.1.0/24 (Nginx web-dmz : 172.20.1.10)
- LAN : 172.20.2.0/24 (DNS dnsmasq : 172.20.2.10, Clients)
- Management : 172.20.3.0/24 (Prometheus, Grafana, Jenkins)
- Router/Firewall : 172.20.1.1 (nftables)
