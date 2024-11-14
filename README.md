# owasp-juice-shop-compose

## juice-shop compose NÉLKÜL:

- létrehozás
  ```sh
  sudo docker run -d -e "NODE_ENV=ctf" -p 3000:3000 --name juice-shop bkimminich/juice-shop
  ```
- futtatás
  ```sh
  sudo docker start juice-shop
  ```
- törlés
  ```sh
  sudo docker rm juice-shop
  ```

## juice-shop compose-al:

- létrehozás
  ```sh
  sudo docker-compose create 
  ```
- futtatás
  ```sh
  sudo docker-compose up
  ```
  VAGY
  ```sh
  sudo docker-compose start
  ```
- törlés
  ```sh
  sudo docker-compose down
  ```
