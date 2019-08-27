# LeonardoMelo-Reposit-rio
# Leonardo Melo-Repositório

enable
configure terminal 
hostname SW-CORE	
interface vlan 1
ip address 192.168.0.254 255.255.255.0
no shutdown
description INTERFACE DE GERENCIAMENTO
do wr


enable 
configure terminal 
line vty 0 15
password SenhaVTY
exit
enable secret SenhaEnable
do wr
