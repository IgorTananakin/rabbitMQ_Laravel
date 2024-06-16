Сама установка rabbitMQ erlang и для windows
https://www.erlang.org/downloads
https://github.com/rabbitmq/rabbitmq-server/releases/download/v3.13.3/rabbitmq-server-3.13.3.exe

Для laravel
1) https://github.com/php-amqplib/php-amqplib
 ### composer require php-amqplib/php-amqplib ###
2) https://www.rabbitmq.com/tutorials
3) Для издателя (публикует)
### php artisan make:command PublishComamand  ### 
в ветке consume 
4) если команда не создалась 
 ### composer dump-autoload ###