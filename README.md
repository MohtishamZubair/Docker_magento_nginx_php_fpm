# Docker_magento_nginx_php_fpm
for magento2 with Docker &amp; docker compose

only run this command by docker-compose after installing docker & docker compose
  docker-compose up -d
  
  It will setup 
  nginx-proxy on host server with its network
  
  nginx server with networks of nginx-proxy, php-fpm, & data
  
  php-fpm has its separate server php_net
  data has its separate server data_net
  

