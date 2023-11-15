markdown

# install-puppeteer

# if you want install nodejs with nvm
complete doc nvm
https://github.com/nvm-sh/nvm?tab=readme-ov-file#install--update-script

```bash
# Install NVM
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
or
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash

# Load NVM into the current shell session
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

#list Node.js Version
nvm ls-remote

# Install Node.js 14.x
nvm install 14.x.x

# Set Node.js 14.x as the default version
nvm use 14.x.x
```

## On CentOS 7/8, Alma Linux 8 & Rocky Linux 8

```bash
# Update the system and install dependencies
sudo yum update -y

# Install curl
sudo yum install -y curl

# Install Node.js 14.x
sudo curl -sL https://rpm.nodesource.com/setup_14.x | sudo bash -
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
