# Readme

docker laradock

git clone https://github.com/Laradock/laradock.git

cp env-example .env

# Fix port container 

Default

nginx 80

mysql 3306

phpmyadmin 8081

# Run your containers
docker-compose up -d nginx mysql phpmyadmin redis workspace 

docker-compose exec workspace bash

php artisan migrate

npm i or npm install

npm run dev or npm run watch

start app http://localhost