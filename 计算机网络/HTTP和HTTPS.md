# HTTP 与 HTTPS

## 1、HTTP 与 HTTPS 有哪些区别？ 

1. HTTP 是超文本传输协议，信息是明文传输，存在安全风险的问题。HTTPS 则解决 HTTP 不安全

的缺陷，在 TCP 和 HTTP 网络层之间加入了 SSL/TLS 安全协议，使得报文能够加密传输。

2. HTTP 连接建立相对简单， TCP 三次握手之后便可进行 HTTP 的报文传输。而 HTTPS 在 TCP

三次握手之后，还需进行 SSL/TLS 的握手过程，才可进入加密报文传输。

3. HTTP 的端口号是 80，HTTPS 的端口号是 443。 

4. HTTPS 协议需要向 CA（证书权威机构）申请数字证书，来保证服务器的身份是可信的。

## 2、HTTPS 解决了 HTTP 的哪些问题？

HTTP 由于是明文传输，所以安全上存在以下三个风险：