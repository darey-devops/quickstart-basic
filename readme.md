- Install php apache mysql
- install composer
- enable mod rewrite in apache
- Download the files and extract them to /var/www/html
- Edit default apache site to point to /var/www/html/public folder
- mv .env.sample .env in /var/www/html
- create mysql database and user
- edit .env with the values from previous step
- run composer install
- run php artisan migrate
- run php artisan db:seed
