berbagi minuman yg mgkn bermanfaat

```
wget -O /usr/bin/dokodok https://raw.githubusercontent.com/18rudi/es_teh/main/dokodok && chmod +x /usr/bin/dokodok
```
cara penggunaan dokodok
1. lock interface by ip modem (misal ip modem 192.168.8.1)
```
dokodok ipgt eth1 eth2 192.168.8.255
```
jadi nanti eth1 akan di lock modem ip modem 192.168.8.1


2. lock interfacw by MAC address
```
dokodok mac eth1 eth2 XX:XX:XX:XX:XX:XX
```
ganti XX:XX:XX:XX:XX:XX dg mac address modemmu

run di terminal dulu untuk testing. setelah di taruh di startup biar lock pas booting

thanks

# es_teh
