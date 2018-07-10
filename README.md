# Dockerized-Nextcloud-SSL

This is the Raspberry PI version of the docker-compose file used here: https://github.com/ichiTechs/Dockerized-SSL-NextCloud-with-MariaDB \n
Follow along his great tutorial but after you pulled his repo substitute this docker-compose.yml in. (Testet on Raspberry PI 2B) \n
By the way I chose to use a 4096 bit certificate, it takes about 1.5 hours to generate. You can decrease the size in the docker-compose file(LETSENCRYPT_KEYSIZE=...).\n
I also changed restart: to on-failure, so it doesnt launch automatically on boot up, you can change it back to always, if you wish to have this behavior.\n
