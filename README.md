# Elemental Battles

- *Account*: `player1`
- *Private Key*: `5KFyaxQW8L6uXFB6wSgC44EsAbzC7ideyhhQ68tiYfdKQp69xKo`


Make sure Docker and Node.js are installed

* Install Docker: https://docs.docker.com/docker-for-mac/install/
* Install Node.js: https://nodejs.org/en/

The DApp and eosio will occupy the ports 3000, 8888 and 9876. Make sure nothing else is already running on these ports.


## Quick start - Run the DApp

```sh
./quick_start.sh
```

The above command will execute the following in sequence:

1. `first_time_setup.sh`
2. `start_eosio_docker.sh`
3. `start_frontend.sh`

- Login with the following credentials:

**To stop**, press `ctrl+c` on your keyboard, and execute:
```sh
docker stop eosio_cardgame_container
```
