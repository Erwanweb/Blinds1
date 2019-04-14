# Blinds1
Blinds group

install :

cd ~/domoticz/plugins

mkdir Blinds1

sudo apt-get update

sudo apt-get install git

git clone https://github.com/Erwanweb/Blinds1.git Blinds1

cd Blinds1

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart

Upgrade :

cd ~/domoticz/plugins/Blinds1

git reset --hard

git pull --force

sudo chmod +x plugin.py

sudo /etc/init.d/domoticz.sh restart
