# MySQL
FROM mysql
# Copier le fichier `beer.sql` du dossier `sql` dans l'entrypoint du conteneur MySQL
COPY beer.sql /docker-entrypoint-initdb.d
# Exposer le port 5000
# EXPOSE 5000:3600
# Exécuter la commande `docker build -t beer .` dans le dossier `docker`
