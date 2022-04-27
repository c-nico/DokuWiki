# DokuWiki

## Run TP

```
sudo apt update
sudo apt install git curl -y
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
git clone https://github.com/c-nico/DokuWiki.git
cd DokuWiki
sudo docker-compose up
```
