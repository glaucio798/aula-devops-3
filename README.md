## Exercicio 01

Executando o docker com o comando bash de modo iterativo:
```shell
    docker run -it ubuntu bash
```

Dentro do docker criado eu executo o comando apt update pra atualizar o repositorio de pacotes:
```shell
    apt update
```

Após isso instalamos o curl propriamente dito:
```shell
    apt install curl
```

E com isso temos acesso ao comando `curl`:
```shell
    curl --version
```

que nos retorna:
```shell
    curl 7.81.0 (x86_64-pc-linux-gnu) libcurl/7.81.0 OpenSSL/3.0.2 zlib/1.2.11 brotli/1.0.9 zstd/1.4.8 libidn2/2.3.2 libpsl/0.21.0 (+libidn2/2.3.2)
    libssh/0.9.6/openssl/zlib nghttp2/1.43.0 librtmp/2.3 OpenLDAP/2.5.16
    Release-Date: 2022-01-05
    Protocols: dict file ftp ftps gopher gophers http https imap imaps ldap ldaps mqtt pop3 pop3s rtmp rtsp scp sftp smb smbs smtp smtps telnet tftp 
    Features: alt-svc AsynchDNS brotli GSS-API HSTS HTTP2 HTTPS-proxy IDN IPv6 Kerberos Largefile libz NTLM NTLM_WB PSL SPNEGO SSL TLS-SRP UnixSockets zstd
```


