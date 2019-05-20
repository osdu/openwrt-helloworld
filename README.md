OpenWrt repository for helloworld
========
Binaries built from this repository on 2019-05-20 can be downloaded from http://osdu.github.io/openwrt-helloworld/.
To install the helloworld package, run
```
echo "src/gz announce http://osdu.github.io/helloworld" >> /etc/opkg.conf
opkg update
opkg install helloworld
```
