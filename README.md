# MAKE SELFSIGNED CERT

openssl req -x509 -newkey rsa:4096 -keyout hivemanager-key.pem -out hivemanager-cert.pem -days 3650 -subj "/C=US/ST=California/L=Sunnyvale/O=Aerohive/OU=Default/CN=HiveManager" -sha256 -nodes
