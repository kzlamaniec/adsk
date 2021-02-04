# Checkpoints

* aws instance
* sokrates ssh
* hosts.ini

``` bash
eval `ssh-agent`
ssh-add ~/.ssh/id_student #ściezka do  klucza
```

* vouchershop.jar // public access

## to do

- [x] ssh access
- [x] install java runtime env
    - sudo yum install https://corretto.aws/downloads/latest/amazon-corretto-11-x64-al2-jre.rpm
- [x] download jar
    - wget https://github.com/kzlamaniec/vouchershop/releases/download/v1.0/voucherShop.jar
- [x] java -jar app.jar --server.port=8080
- [x] define dir structure /opt/voucherShop
    /usr/bin/java  -jar  /opt/voucherShop/voucherShop.jar
    
- [x] setup as background service
- [x] start on boot

- [ ] automate via ansible


## todo

- install app_nodes

- [ ] EPEL REPO
- [ ] install nginx
- [ ] configure proxy to app node
- [ ] declare instalation via ansible
- [ ] reconfigure proxy -> lb
- [ ] add 1 more app node
- [ ] test lb settings
