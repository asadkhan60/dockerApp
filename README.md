# dockerApp installation

- docker-compose build
- docker-compose up -d
- connect to your php container : docker-compose exec php bash
- install project dependencies : composer install
- go to localhost:8080


# Containers connections

- MySQL : docker-compose exec mysql bash
- PHP : docker-compose exec php bash
- Apache : docker-compose exec apache bash
