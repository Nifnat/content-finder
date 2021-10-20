# content-finder

# Setup
## Env fie
Make `.env` with `CYTUBE_URL`, `CYTUBE_URL_CHANNEL_NAME`, `CYTUBE_USERNAME`, `CYTUBE_PASSWORD`,
`CYTUBE_USER_AGENT` and `CYTUBE_COOKIE`.

Something like:
```
CYTUBE_URL=https://cytu.be/
CYTUBE_URL_CHANNEL_NAME=my_channel
CYTUBE_USERNAME=my_username
CYTUBE_PASSWORD=my_password
CYTUBE_USER_AGENT=
CYTUBE_COOKIE=
```

## Channels
Add channel ids and channel names to `channel-ids.txt`, e.g.:
```
# channel name 1
channel_id_1
# channel name 2
channel_id_2
```

# Running
## Docker compose
`docker-compose up`
## No docker
Assuming bash shell:
```
python -m virtualenv venv
source venv/Scripts/activate
pip install -r requirements.txt
python main.py
```