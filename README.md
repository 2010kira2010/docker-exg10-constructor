# Constructor Telegram Bots EXG10

# Installing
```bash
cd /opt
git clone https://github.com/2010kira2010/docker-exg10-constructor.git Telegram-Bots
cd /opt/Telegram-Bots

git clone https://github.com/EXG1O/Constructor-Telegram-Bots-Frontend.git frontend
git clone https://github.com/EXG1O/Constructor-Telegram-Bots.git constructor
git clone https://github.com/EXG1O/Telegram-Bots-Hub.git hub

# Change the value of the variables to your liking .env, .env.constructor, .env.hub
mv .env.constructor ./constructor/.env
mv .env.hub ./hub/.env
mv Dockerfile.constructor ./constructor/Dockerfile
mv Dockerfile.hub ./hub/Dockerfile

docker compose up -d
```

# Update
```bash
cd /opt/Telegram-Bots/frontend
git pull

cd /opt/Telegram-Bots/constructor
git pull

cd /opt/Telegram-Bots/hub
git pull
```

## Contributing
Read [CONTRIBUTING.md](CONTRIBUTING.md) for more information on this.

## License
This repository is licensed under the [AGPL-3.0 License](LICENSE).