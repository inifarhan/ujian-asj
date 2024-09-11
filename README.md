# ujian-asj

1. nano /etc/network/interfaces 
    - auto eth0
      iface eth0 inet dhcp
    - auto eth1 
      iface eth1 inet static 
      address 10.10.10.33/24
      gateaway ( cek d cmd / ketik          
      ip r ) 192.168.250.1 
2. service networking restart 
3. cek ip perintahnya ( ip a ) cek ip dan cek ping 8.8.8.8
4. nano /etc/apt/sources.list
- deb http://kartolo.sby.datautama.net.id/debian/ buster main contrib non-free 
- deb http://kartolo.sby.datautama.net.id/debian/ buster-updates main contrib non-free 
- deb htttp://kartolo.sby.datautama.net.id/debian-security/ buster/updates main contrib non-free 
5. apt-get update ( tunggu sampe 21 ) 
6. wget -O ehcp.tgz www.ehcp.net/ehcp_latest.tgz 
7. tar -zxvf ehcp.tgz
8. cd ehcp
9. ./install.sh 
10. enter enter aja, nnt ketik y ajaa kl ada yg d suru ketik itu
11. nnt ada ( : ) ketik q 
12. nnt ada d suru ngetik bahasa ketik = en aja lalu enter
13. nnt kl uda muncul 'root@debian:~/ehcp#' ketik ip a
14. kalo uda dapet ip nya masukin k browser 
15. kl udaa masuk brrt berhasil



note : pastiin dapet internet, password jangan sampe lupa.
