# Overview

Nginx Proxy Manager is a useful tool for adding a Nginx front-end to Dockerized applications.  This set of recipes are ones that I've modified from their original sources to work with Docker Compose.

The basic configuration requires a Docker network called `npm_dmz`.  This DMZ is where NPM communicates with the other applications.  The other applications should have their own private network for their container components

To create `npm_dmz`:

```docker network create -d bridge npm_dmz```

# Recipes
- [Nginx Proxy Manager](https://nginxproxymanager.com/)
- [WordPress](https://wordpress.org)
- [WikiJS](https://js.wiki/)
- [Metabase](htts://metabase.com)
- [Airbyte](https://airbyte.io/)
