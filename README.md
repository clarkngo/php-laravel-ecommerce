# php-laravel-ecommerce
Create Ecommerce Restful API

Laravel 5.5
https://laravel.com/docs/5.5/eloquent-resources
Getting Started -> Installation -> Composer
Download Composer -> Install
https://getcomposer.org/download/
Move to Global (PATH)
https://getcomposer.org/doc/00-intro.md
Go back to https://laravel.com/docs/5.5/installation

Terminal:
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');" php -r "if (hash_file('SHA384', 'composer-setup.php') === '544e09ee996cdf60ece3804abc52599c22b1f40f4323403c44d44fdfdd586475ca9813a858088ffbc1f233e9b180f061') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;" php composer-setup.php php -r "unlink('composer-setup.php');”
mv composer.phar /usr/local/bin/composer

Terminal:
composer global require "laravel/installer”

Installation location:
~/.composer/vendor/bin/laravel

Terminal:
laravel new eapi

