## Esegue PHP e APACHE in un container usando come cartella del sito sito_php
## Espone il sito sulla porta http://localhost:8080
docker run -d -p 8080:80 --name apache-php -v /home/daniele/Documenti/informatica-github/site/sito-php:/var/www/html php:7.2-apache

# vedi cosa è in esecuzione
docker ps