# Quickstart

docker-compose up -d

edit /etc/hosts

127.0.0.1 drupal.docker.localhost drupal2.docker.localhost pma.drupal.docker.localhost adminer.drupal.docker.localhost mailhog.drupal.docker.localhost solr.drupal.docker.localhost nodejs.drupal.docker.localhost front.drupal.docker.localhost varnish.drupal.docker.localhost portainer.drupal.docker.localhost webgrind.drupal.docker.localhost

https://wodby.com/docs/stacks/drupal/local/#domains


modify .env config from this fork
https://github.com/wodby/docker4drupal/pull/367/commits/5eb6817680e3ffd4572566532440b31e65c31067

browse to
http://drupal.docker.localhost:8000

and
http://drupal2.docker.localhost:8000

I guess you need to make 2 databases, haven't checked if docker-compose or phpmyadmin?


# House-keeping

docker-compose down && docker-compose up
