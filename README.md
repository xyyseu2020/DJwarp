```
wget -N --no-check-certificate https://cdn.jsdelivr.net/gh/ygkkk/DJwarp/DJwarp.sh && chmod +x DJwarp.sh && ./DJwarp.sh
```
进入脚本快捷方式 ```bash DJwarp.sh```

- [刷新脚本](https://purge.jsdelivr.net/gh/kkkyg/DJwarp/DJwarp.sh)

DIG用户请先执行

```
echo -e "search blue.kundencontroller.de\noptions rotate\nnameserver 2a02:180:6:5::1c\nnameserver 2a02:180:6:5::4\nnameserver 2a02:180:6:5::1e\nnameserver 2a02:180:6:5::1d" > /etc/resolv.conf
```
