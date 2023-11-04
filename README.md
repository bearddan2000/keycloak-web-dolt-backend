# keycloak-web-dolt-backend

## Description
Keycloak is an open source identity provider.
Deminstrates importing json file, a single user.

| type | user | password |
| ---- | ---- | -------- |
| keycloak user | keycloak | test |
| keycloak admin | admin | pass |
| database admin | root |  |

Mysql database to replace default.

#### tech stack
- keycloak
- dolt

## Docker stack
- jboss/keycloak:latest
- dolthub/dolt-sql-server

## To run
`sudo ./install.sh -u`
- [Availble](http://localhost)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
