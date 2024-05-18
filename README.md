# Web Wake On Lan
This is a simple website for using wake on lan outside of your home network. It runs on nodejs

## Requirements
- nodejs
- npm

## Setup

#### 1. Clone the repository and change directory
```bash
git clone https://github.com/bbara04/WebWOL.git
cd WebWOL
```

#### 2. Set ip in config yaml
Open config.json and set the ip address to your targets ip

#### 3. Install Nodejs, NodePacketManager and start the webpage
```bash
sudo apt install nodejs
sudo apt install npm
node server.js
```

## Screenshots
![alt text](https://github.com/bbara04/WebWOL/blob/main/blob/WebView.png?raw=true)
