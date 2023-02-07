mmumshad/kubernetes-the-hard-way

MV (VirtualBox)
IP 192.168.56.0/24
Esta configurado en el 'Vagranrfile' en la line 9

Pod Network
IP 10.244.0.0/16
POD_CIDR=10.244.0.0/16

Service Network
IP 10.96.0.0/16
SERVICE_CIDR=10.96.0.0/16

Service DNS
IP 10.96.0.10
coredns.yaml line 185
