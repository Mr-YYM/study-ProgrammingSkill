## 一、HTTP 形式

### 走 HTTP 代理

```shell
git config --global http.proxy "http://127.0.0.1:1087"
git config --global https.proxy "http://127.0.0.1:1087"
```

### 走 socks5 代理（如 Shadowsocks）

```shell
git config --global http.proxy "socks5://127.0.0.1:1086"
git config --global https.proxy "socks5://127.0.0.1:1086"
```

### 取消设置

```shell
git config --global --unset http.proxy
git config --global --unset https.proxy
```


