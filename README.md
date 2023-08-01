
# Required
- DOMAIN (HARUS PUNYA)
- DEBIAN 9/10/11
- Ubuntu 18/20/21/22 (rekomendasi Ubuntu 20.04) 
- CPU MINIMAL 1 CORE
- RAM 1GB

</p> 
<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p> 
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=purple"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=Lts&color=red"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
</p>

### INSTALL SCRIPT
<pre><code>apt install -y wget screen && apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && wget -q https://raw.githubusercontent.com/effatastore/effata/ipsc/main.sh && chmod +x main.sh && screen -S install ./main.sh</code></pre>


### TESTED ON OS 
- UBUNTU 20.04.05

### FITUR TAMBAHAN
- Tambah Swap 1GiB
- Pemasangan yang dinamis
- Tuning profile pada server
- Xray Core by [@dharak36](https://github.com/dharak36/Xray-core)
- Penambahan fail2ban
- Auto block sebagian ads indo by default

### PORT INFO
```
- TROJAN WS 443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- VLESS WS 443
- VLESS GRPC 443
- VLESS NONTLS 80
- VMESS WS 443
- VMESS GRPC 443
- VMESS NONTLS 80
- SSH WS / TLS 443
- SSH NON TLS 8880
- OVPN SSL/TCP 1194
- SLOWDNS 5300
```

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```
### STATUS
`Beta Testing`

### Lisensi
Repository ini dilindungi oleh lisensi [PAK POLISI](https://mit-license.org/)

### Credits
- [Dharak36](https://github.com/dharak36/Xray-core)
- [Tiarap](https://github.com/pengelana/blocklist)
