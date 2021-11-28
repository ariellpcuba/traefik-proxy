#Traefik Proxy for hosting WebServices +Docker


-  Modify docker-compose for exposing ports that you need(80/443).
-  Create docker network proxy.
-  Modify traefik/traefik.yml   and traefik/config.yml.
-  Create a certs folders and generate certs inside of it.
-  Generate a password with package `apache-utils`  using `htpasswd -traefik/.htpasswd proxy`
-  Use the content of .htpasswd in traefik/config.yml
