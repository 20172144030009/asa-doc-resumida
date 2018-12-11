# Configuração de interface de rede
Aqrquivo :file:'/etc/netplan'<tab> (para ubuntu)
network:
   ethernets:
       enp0s3:
           addresses: []
           dhcp4: true
           optional: true
        enp0s8:
           addresses: [colaca-se o ip /24]
           dhcp4: false
   version: 2

* comando: sudo netplan try
* comando: sudo netplan apply
