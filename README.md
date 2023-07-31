auto enable udp proxy openclash

install

```
wget --no-check-certificate "https://raw.githubusercontent.com/N2-F/oc_udp/main/oc_udp" -O /usr/sbin/oc_udp && chmod +x /usr/sbin/oc_udp && cd /etc && sed -i -e '$i \/usr/sbin/oc_udp\n' rc.local

```
#sudah otomatis enable saat booting, tidak perlu lagi mengedit di bagian startup
