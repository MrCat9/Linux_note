# Linux_note

## 拷贝文件到本地，拷贝本地文件到远程服务器

拷贝远程服务器的文件到本地：
```
scp -P [端口号] [用户名]@[IP地址]:[服务器上的文件地址] [本地文件夹地址]
```

拷贝本地文件到远程服务器：
```
scp -P [端口号] [本地文件地址] [用户名]@[IP地址]:[服务器上的文件夹地址]
```
