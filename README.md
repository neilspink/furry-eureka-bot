# furry-eureka-bot

## Infrastructure

```
ansible-galaxy collection install community.mongodb
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
