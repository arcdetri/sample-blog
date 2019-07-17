# Sample Blog

First install your web server (e.g. Apache, Nginx, Caddy).

If necessary, create the web root directory `/var/www/html/`.

Then download the content for the sample blog as follows.

## Debian or Ubuntu

```
sudo apt install wget zip unzip
cd ~/Downloads
wget https://github.com/arcdetri/sample-blog/archive/master.zip
unzip master.zip
sudo cp -rf blog/html/* /var/www/html/
```

## CentOS

```
sudo yum install wget zip unzip
cd ~/Downloads
wget https://github.com/arcdetri/sample-blog/archive/master.zip
unzip master.zip
sudo cp -rf blog/html/* /var/www/html/
```
