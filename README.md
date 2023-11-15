# install-puppeteer
install-puppeteer

# **on centos 7/8 alma linux 8 & rocky linux 8**

yum update -y

yum install -y curl

sudo curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -

sudo yum install -y nodejs

sudo yum install atk java-atk-wrapper at-spi2-atk gtk3 libXt libdrm mesa-libgbm nss libdrm mesa-libgbm

go to your website root 

sudo npm install --save puppeteer@~17.1.3

done


# **on ubuntu 20.04, 22.04**

sudo apt-get update

sudo apt update

sudo apt install -y curl

sudo curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -

sudo apt install -y nodejs

sudo apt-get install npm

sudo apt install libgconf-2-4 libatk1.0-0 libatk-bridge2.0-0 libgdk-pixbuf2.0-0 libgtk-3-0 libgbm-dev libnss3-dev libxss-dev

go to your website root 

sudo npm install --save puppeteer@~17.1.3

done
