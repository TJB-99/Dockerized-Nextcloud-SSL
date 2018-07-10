# Dockerized-Nextcloud-SSL

This is the Raspberry PI version of the Docker-Compose file used here:
Substitute it in and leave everything else as it is and it should work. (Testet on Raspberry PI 2B) 
By the way I chose to use a 4096 bit certificate, it takes about 1.5 hours to generate. You can decrease the size in the docker-compose file(LETSENCRYPT_KEYSIZE=...).
