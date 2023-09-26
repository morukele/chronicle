### How to run this project


#### obd part and directory of the project
- Download [elm](https://github.com/Ircama/ELM327-emulator)

- run `elm` simply `elm -s car`

- then `cd` into **obd** directory and create your `venv`
- install requirements by running `pip install -r requirements.txt`
- Then run `python server.py`

#### web directory of the project
to enter this directory, cd into `web`

- create container by running `docker pull timescale/timescaledb:latest-pg14`
- create a postgres db using docker and name it `onboardpi-dev`
- run `npm install`
- run `node server.js`

#### client directory of the project
to enter this directory, cd into `web`, then cd into `client`

- download [nvm]() and change your node version to version 16.0.0
- run `npm install`
- run `npm start`