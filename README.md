markdown

# install-puppeteer

## On CentOS 7/8, Alma Linux 8 & Rocky Linux 8

```bash
# Update the system and install dependencies
sudo yum update -y

# Install curl
sudo yum install -y curl

# Install Node.js 14.x
sudo curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -
sudo yum install -y nodejs

# Install additional dependencies
sudo yum install -y atk java-atk-wrapper at-spi2-atk gtk3 libXt libdrm mesa-libgbm nss

#Navigate to your website root

cd /path/to/your/website

#Install Puppeteer version 17.1.3

sudo npm install --save puppeteer@~17.1.3
```

## On Ubuntu 18.04, 20.04, 22.04

```bash
#Update the system and install dependencies

sudo apt-get update
sudo apt update

# Install curl
sudo apt install -y curl

# Install Node.js 14.x
sudo curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -
sudo apt install -y nodejs

# Install npm
sudo apt-get install npm

# Install additional dependencies
sudo apt install -y libgconf-2-4 libatk1.0-0 libatk-bridge2.0-0 libgdk-pixbuf2.0-0 libgtk-3-0 libgbm-dev libnss3-dev libxss-dev

#Navigate to your website root

cd /path/to/your/website

#Install Puppeteer version 17.1.3

sudo npm install --save puppeteer@~17.1.3
```
