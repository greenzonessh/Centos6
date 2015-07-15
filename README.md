centos6
======

CentOS 6 Scripts for VPS &amp; SSH Seller by Yuri Bhuana


Autoscript Include:
=============

Service
-------
OpenSSH  : 22, 143
Dropbear : 109, 110, 443
OpenVPN  : 1194 (client config : http://IPVPS:81/client.tar)
badvpn   : badvpn-udpgw port 7300
PPTP VPN  : Create User via Putty (echo username pptpd password * >> /etc/ppp/chap-secrets)
Squid    : 80, 8080 (limit to IP SSH)
nginx    : 81

Tools
-----
axel, bmon, htop, iftop, mtr, nethogs


Script
------
screenfetch



./ps_mem.py (Cek RAM)
./speedtest_cli.py --share (Speed Test VPS)
./bench-network.sh (Cek Kualitas VPS)
user-expire.sh (Auto Lock User Expire tiap jam 00:00)
./user-list (Melihat Daftar User)
./user-login.sh (Monitoring User Login Dropbear, OpenSSH dan PPTP VPN)

Fitur lain
----------
Webmin   : http://IPVPS:10000/
vnstat   : http://IPVPS:81/vnstat/ (Cek Bandwith)
MRTG     : http://IPVPS:81/mrtg/
Timezone : Asia/Jakarta (GMT +7)
Fail2Ban : [on]
IPv6     : [off]
Autolimit 2 bitvise per IP to all port (port 22, 143, 109, 110, 443, 1194, 7300 TCP/UDP)

Script Modified by Yuri Bhuana (fb.com/youree82, 0858 1500 2021)
Thanks to Original Creator Kang Arie & Mikodemos

Log Instalasi --> /root/log-install.txt

VPS AUTO REBOOT TIAP 6 JAM, SILAHKAN REBOOT VPS ANDA !

===================================================
