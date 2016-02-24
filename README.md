# openssl-utils

Some scripts to automate the creation of SSL Certs.

##Easy Install
```sh
$./install.sh
```

### Create a CA Authority 
```sh
$./createCA -c /opt/ssl -d kisspi.com
```

### Create Keys for the server
```sh
$./createServerKeyAndSign -c /opt/ssl -d kisspi.com 
```

### Create Keys for client
```sh
$./createClientCert -c /opt/ssl -n myphone
```
