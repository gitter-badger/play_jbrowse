## JBrowse

[![Join the chat at https://gitter.im/BioCloud-TW/play_jbrowse](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/BioCloud-TW/play_jbrowse?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Install JBrowse

http://jbrowse.org/install
    http://gmod.orgwiki/JBrowse

## System Requirments

sudo apt-get install libpng-dev libgd2-noxpm-dev bulid-essential

## Download and Uncompress JBrowse

sudo mkdie /var/www/
wget http://jbrowse.org/release/JBrowse-x.x.x.zip
unzip JBrowse-x.x.x.zip
cd JBrowse

## Install web server 
## nginx

sudo apt-get install nginx
sudo service nginx start

## check web werver status

telent localhost 80
