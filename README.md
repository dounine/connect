# connect
socks5 convert git protocol

## How to Use
```
make
```

## use for git protocol
```
cat ~/.ssh/config
```
content
```
Host github.com
  HostName github.com
  ProxyCommand $path/connect -S 127.0.0.1:1080 %h %p
```
