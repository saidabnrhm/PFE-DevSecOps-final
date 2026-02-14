FROM nginx:alpine

# Supprimer la config par défaut
RUN rm -rf /usr/share/nginx/html/*

# Copier le code frontend tel quel (même s’il n’est pas buildé)
COPY . /usr/share/nginx/html

EXPOSE 80