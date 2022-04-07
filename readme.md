# TeamWin-TF2-Server
This is a docker-compose template for the TeamWin-TF2-Server

## How to use:

1. Get yourself a game server token from Steam [here](https://steamcommunity.com/dev/managegameservers).
2. Then get yourself a Steam Web Api key from [here](https://steamcommunity.com/dev/apikey).
3. Create a file named `.env` and populate it with the following (replacing the values here with real ones):
```
SRCDS_TOKEN=${GAME_SERVER_TOKEN}
SRCDS_WORKSHOP_AUTHKEY=${WEB_API_KEY}
SRCDS_PW=${SERVER_PASSWORD}
SRCDS_RCONPW=${SERVER_RCON_PASSWORD}
```
4. Then run `docker-compose up -d`
