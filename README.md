# Docker_magento_nginx_php_fpm
for magento2 with Docker &amp; docker compose. This is soley for exploration of docker ecosystem aiming towards deployment of magento2 on nginx with php-fpm 7. Maintainer is not resposible for any undesired situations.


First install docker & docker-compose
It does need nginx-proxy first installed on docker host server then its network must be set in docker-compose file under default in place of  name: dockercompose_local-app-net.

only run this command by docker-compose after installing docker & docker compose
  
  docker-compose up -d
  
  It will setup nginx server with php-fpm has its separate server on separate network php_net
  
  
  ##changes to make in docker-compose file
  1- To replace the nginx-proxy server need to be installed separately by 
   name: dockercompose_local-app-net
  
  2- Also need to have to testing files for web server in mount path

  3- Change the name of domain
