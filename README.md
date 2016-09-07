# Drupal 8 NBB Module

## Test

``bash
cp .env.example .env
docker-compose up -d
# > Navigate to localhost:8080
# > For database configuration use .env
# > Change host from 'localhost' to 'mysql' under Advanced Settings

# docker exec -it drupalnbbmodule_drupal_1 sh -c 'php -r "readfile(\"https://s3.amazonaws.com/files.drush.org/drush.phar\");" > /usr/local/bin/drush && chmod +x /usr/local/bin/drush'
``

## License

This software is licensed under the [MIT license](https://github.com/Cangeroes/drupal-nbb-module/blob/master/LICENSE).

© 2016 Cangeroes
