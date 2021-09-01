# Orion

Orionに対して外部からアクセスします

<pre>https://[[HOST_SUBDOMAIN]]-1028-[[KATACODA_HOST]].environments.katacoda.com/</pre>

`wget https://raw.githubusercontent.com/telefonicaid/fiware-orion/master/docker/docker-compose.yml`{{execute}}

`docker-compose up -d`

`docker ps`

`curl https://[[HOST_SUBDOMAIN]]-1028-[[KATACODA_HOST]].environments.katacoda.com/`{{execute}}
