# oc_udp
auto enable udp proxy openclash

install 

```
wget --no-check-certificate "https://raw.githubusercontent.com/N2-F/oc_udp/main/oc_udp" -O /usr/sbin/oc_udp && chmod +x /usr/sbin/oc_udp
```

tambahkan ke **``LuCI -> System -> Startup -> Local Startup``**

```
/usr/sbin/oc_udp
```
