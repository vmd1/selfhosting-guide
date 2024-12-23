# Authelia - A lightweight SSO provider

Find more info @ https://authelia.com

## Prerequisites
A reverse proxy (In this case I will be using NGINX Proxy Manager)
A redis instance
An LDAP server (In this case I will be using LLDAP due its ease of use and WebUI)

## Initial Configuration
Before we can start, we need to configure authelia. 

## Compose
Similar to the rest of this setup, the compose files are places in their respective directory in /srv/compose (e.g. /srv/compose/authelia).

Assuming you kept all the networks the same as what's listed in the prior guides, you can use this compose file as is.

In the command line:
`docker compose up -d`

or in Dockge, click new stack, paste the attatched compose, and click deploy.
