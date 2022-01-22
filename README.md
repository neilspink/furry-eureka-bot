# furry-eureka-bot

## Infrastructure

```
ansible-galaxy install community.mongodb.mongodb_linux
```

Fails with sorry, community.mongodb.mongodb_linux was not found on https://galaxy.ansible.com/api/

```
sudo apt remove ansible && sudo apt --purge autoremove

sudo apt update
sudo apt upgrade
sudo apt install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
ansible --version
```

## BOT

 In the /bot folder start by installing python packages

```
pip3 install -r requirements.txt
```

Make a .env file in bot folder

```
DISCORD_TOKEN=XXX
```

Run program
```
python3 main.py
```

Adding bot to Discord channel

https://discordapp.com/oauth2/authorize?client_id=CLIENTID&scope=bot
