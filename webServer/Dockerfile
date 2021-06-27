#----------------------------------------------
#
# Um servidor web baseado no busybox.
#
# docker build . -t img_ws01
# docker rm web; docker run --name web -it -v ~/dev/webServer/www:/home/www -p 8080:80 img_ws01
#----------------------------------------------

FROM busybox

RUN     mkdir /home/www

ENV     LANG=C.UTF-8
ENV     TZ=America/Sao_Paulo
ENV     LC_ALL=C.UTF-8

#Inicia serviço
CMD     /bin/httpd -p 80 -h /home/www && \
        sh


