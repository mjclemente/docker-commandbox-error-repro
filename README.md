With the current setup in docker-compose.yml, if I run `docker-compose up`, it errors.

It works fine if any of the following things are changed:

1. It uses Lucee instead of ACF
2. The admin password is not set
3. The image is switched to `ortussolutions/commandbox:latest`
