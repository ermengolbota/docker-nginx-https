FROM nginx


#Posem dins de la imatge els certificats que "hem generat / ens han donat"
COPY ./certificats/ /etc/nginx/ssl/

#Posem dins de la imatge els certificats que "hem generat / ens han donat"
COPY ./nginx.conf /etc/nginx/conf.d/default.conf


# HEm de consultar la documentació oficial de la imatge
# per saber les rutes que fa servir
# https://hub.docker.com/_/nginx
COPY ./web /usr/share/nginx/html