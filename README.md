# nginx-tutorial
https://youtu.be/XNklOKmh3Q0

--------- Install Nginx ---------

sudo dnf update -y 

sudo dnf install -y nginx

sudo systemctl start nginx
sudo systemctl enable nginx

sudo firewall-cmd --permanent --add-service=http
sudo firewall-cmd --permanent --add-service=https
sudo firewall-cmd --reload

Navigate to: http://server_ip
