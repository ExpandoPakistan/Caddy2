# Caddy2 with docker-compose

This is a utility repo for quick deployment of caddy2. Caddyfile is loaded into the container when it starts, and two directories 'config' and 'data' are mounted at /config and /data for persistance.


Just edit Caddyfile as you wish and run 'docker-compose up' to start the service.


### NOTE: This container uses "host" as the network_mode so it will listen on the host ip address. Its like installing caddy without doing apt-get or something similar.


Enjoy!

# LICENSE

MIT
