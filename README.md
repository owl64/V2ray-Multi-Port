# V2ray-Multi-Port
Update OS
```
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

Testing Script
```
wget https://raw.githubusercontent.com/fisabiliyusri/XRAY-MANTAP/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

Add Domain
```
mkdir -p /etc/xray
cat >/etc/xray/domain <<EOF
sg01.sshvip.my.id
EOF
```

Lakukan Pointing Ke cloudflare, mengikuti Domain di atas
