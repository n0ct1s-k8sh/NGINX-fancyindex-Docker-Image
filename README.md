# NGINX-FancyIndex-Default-Site-Docker-Image
Latest NGINX Docker Image based on Alpine, with fancyindex module built and enabled and a default virtual site. All ready to deploy.

- The _fancyindex_ module is compiled (cloned from [aperezdc repo](https://github.com/aperezdc/ngx-fancyindex)) with the container's NGINX version sources.
- After that, the module is enabled in the _nginx.conf_ file.
- Finally, a new virtual site is enabled as the default site, with its root directory in _/var/www/content_

## About me
I'm a cloud sysadmin, that tries to dockerize and automate everything that exists. Also, I play the oboe :)
