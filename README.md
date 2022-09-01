# Learn-OpenSSL

- certutil -dump cert.pem
- certutil -hashfile file OPTION(Algorithm: sha1, md5)
- https://www.cryptool.org/en/cto/openssl
- openssl [comand] [param]
- openssl version -a
- openssl rand -hex [number]
- uuid : Numero que identifica um processo(Data, hora e segundo)
- openssl enc -aes-128-cbc -e -in teste.txt -k 1234 -pbkdf2 -a
- openssl enc -aes-128-cbc -d -in teste.txt -k 1234 -pbkdf2 -a
- openssl dgst teste.txt
- openssl dgst -hmac 
