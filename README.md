# About
Softsun Virtual Machine Web UI is a web based graphical user interface that you can easily use to create and configure your virtual machines, virtual storage, virtual network interfaces etc. It is designed to run on nginx with PHP 7.0, but it might work well on other web servers and different PHP versions.

# Installation
There are 2 options how to install this software:

1. Install the whole virtual server on clean Debian installation:
- in this case, follow these instructions: https://github.com/softsun-cz/vm-install/blob/master/README.md

2. Install just this Web UI to your web server

```sh
apt-get -y install git
git clone https://github.com/softsun-cz/vm-webui.git
mv vm-webui/src/* /var/www/html/
rm -rf vm-webui
```
If you have web server root in different path than **/var/www/html/**, please replace it with your actual server root path.
