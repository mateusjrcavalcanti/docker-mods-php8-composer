# PHP8 - Docker mod for code-server

This mod adds php8.0 and composer to code-server, to be installed/updated during container start.

In code-server docker arguments, set an environment variable `DOCKER_MODS=mateusjrcavalcanti/docker-mods-php8-composer:latest`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=mateusjrcavalcanti/docker-mods-php8-composer:latest|linuxserver/mods:code-server-mod2`