# Setup Steps – Ubuntu Server Project

## 1. Install NGINX
sudo apt install nginx -y

## 2. Start NGINX
sudo systemctl start nginx

## 3. Create Web UI
Edit /var/www/html/index.html

## 4. Install Netdata
sudo apt install netdata -y

## 5. Configure Netdata
bind socket to IP = 0.0.0.0

## 6. Access Services
- Web UI → Port 80  
- Netdata → Port 19999
