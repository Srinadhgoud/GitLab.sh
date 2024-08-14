Use this commands for gitlab installation

sudo apt install ca-certificates curl openssh-server postfix tzdata perl cd /tmp curl -LO
https://packages.gitlab.com/install/r...less /tmp/script.deb.sh chmod u+x script.deb.sh ./script.deb.sh (or) sudo bash /tmp/script.deb.sh
sudo apt install gitlab-ce 
sudo ufw allow http 
sudo ufw allow https 
sudo ufw allow OpenSSH 
sudo nano /etc/gitlab/gitlab.rb 
sudo gitlab-ctl reconfigure 
sudo nano /etc/gitlab/initial_root_password
