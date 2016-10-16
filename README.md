# sma-bluetooth

This is a fork of [sma-bluetooth](https://github.com/sma-bluetooth/sma-bluetooth).

# Compiling

## Prerequisites

Quick command to install prerequsites I was missing on Raspian:
````
$ sudo apt-get install  libbluetooth-dev libcurl4-openssl-dev libmysqlclient-dev libxml2-dev libxslt1-dev
````

For some weird reason I also needed to:

````
sudo ln -s /usr/include/libxml2/libxml /usr/include/libxml
````
