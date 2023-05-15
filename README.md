- change db connection strings `DATABASE_URL="mysql://root:root-root@127.0.0.1:3306/shop_cart_db"` in .env file
- you can use docker RUN `docker-compose up -d` OR local environment 
- composer install
- symfony console doctrine:migrations:migrate && symfony console doctrine:fixtures:load
- symfony server:start -d

