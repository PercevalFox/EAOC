# FROM : Image de base
# "alpine" est une distribution Linux ultra-légère (quelques Mo seulement).
# Nous utilisons ici la version d'Apache optimisée pour Alpine.
FROM httpd:2.4-alpine

# WORKDIR : Définit le répertoire de travail dans le conteneur.
# Même sous Alpine, l'image officielle httpd utilise ce chemin standard.
WORKDIR /usr/local/apache2/htdocs/

# COPY : Copie votre fichier index.html local vers le dossier du conteneur
# Le "." correspond au WORKDIR défini juste au-dessus.
COPY ./index.html .

# EXPOSE : Indique que le conteneur écoute sur le port 80 (HTTP)
EXPOSE 80
