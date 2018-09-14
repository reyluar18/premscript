# Premium AutoScript

Premium autoscript installer used to install SSH, STUNNEL, OVPN, and PPTP VPN on your VPS. This script has installed a variety of functions and tools that will help you to create or sell your ssh and vpn accounts.

### Installation:

- Centos 6 x86 & x64

`yum -y update && yum -y install wget && wget https://raw.githubusercontent.com/reyluar18/premscript/master/FFAST_Centos6 && chmod +x FFAST_Centos6 && ./FFAST_Centos6 && rm -f FFAST_Centos6 && history -c`



- Centos 7 (OVPN not included)

`yum -y update && yum -y install wget && wget https://raw.githubusercontent.com/reyluar18/premscript/master/FFAST_Centos7 && chmod +x FFAST_Centos7 && ./FFAST_Centos7 && rm -f FFAST_Centos7 && history -c`



- Debian 7 x86 & x64

`apt-get -y install wget && wget https://raw.githubusercontent.com/reyluar18/premscript/master/FFAST_Debian7 && chmod +x FFAST_Debian7 && ./FFAST_Debian7 && rm -f FFAST_Debian7 && history -c`



- Debian 8 x86 & x64

`apt-get -y install wget && wget https://raw.githubusercontent.com/reyluar18/premscript/master/FFAST_Deb8 && chmod +x FFAST_Deb8 && ./FFAST_Deb8 && rm -f FFAST_Deb8 && history -c`




### Important Information:

- Fail2Ban

- Ddos Deflate

- IP Tables

- Webmin - http://VPSIP:10000/

- VnStat - http://VPSIP:85/vpnstat/

- MRTG - http://VPSIP:85/mrtg/

- OVPN Config - http://VPSIP:85/client.ovpn | http://VPSIP:85/openvpn.tar.gz or http://VPSIP:85/client.tar for Centos


### Service and Port Informations:

- OpenVPN : TCP 1194

- OpenSSH : 22 & 143

- Stunnel/4 : 443

- Dropbear : 109, 110 & 442

- Squid Proxy : 80, 8000, 8080, 8888 & 3128

- PPTP VPN : 1732

- Badvpn : 7300

- Nginx : 85


### Server Tools:

- htop

- iftop

- mtr

- nethogs

- screenfetch


### Credits:

Hosting Termurah & VPS-Murah







Created by 0123456
