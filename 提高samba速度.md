
vim smb.conf
添加下面代码
```
read size = 32768
read prediction = true
socket options = TCP_NODELAY SO_RCVBUF=16384 SO_SNDBUF=16384
```