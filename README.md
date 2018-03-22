This Docker wordpress imgage was created to include support for increase file upload sizes and php max execution times inside php.ini as well as .htaccess method.
It comes preloaded with WP-CLI, compose and memcahced. This image is derived from Christian Chung's <christian.m.chung@gmail.com> custom wordpress image, but with the above mentioned modifications.
It also predefines values for Mycred, mainly to support the [Tetoka Financial Literacy LMS](https://Tetoka.co "Tetoka Learning System"). These values are included by default in this image's wp-config.php file. More work is currently being done to include the actual points management system into this image as a dependency. This is the official Wordpress imgage used by the [Tetoka Learning Management System](https://tetoka.co "Tetoka"). 
# WordPress & Memcached Image

### Loads:
 - Memcached
 - wp-cli
 - composer
 - object-cache.php
 - advanced-cache.php
