auto enable udp proxy openclash

instalasi

copy dan jalankan via terminal

```
wget --no-check-certificate "https://raw.githubusercontent.com/N2-F/oc_udp/main/oc_udp" -O /usr/sbin/oc_udp && chmod +x /usr/sbin/oc_udp && sed -i -e '$i /usr/sbin/oc_udp\n' /etc/rc.local && oc_udp


```
