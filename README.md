# nginx-docker-letsencrypt
Basic boilerplate to combine let's encrypt with nginx in a docker environment


## how-to

1. Make init-letsencrypt.sh executable and run it:
    ```
   chmod +x init-letsencrypt.sh
   sudo ./init-letsencrypt.sh
   ```

2. Run with docker-compose production file
    ```
    docker-compose -f docker-compose-production.yaml up
    ```
