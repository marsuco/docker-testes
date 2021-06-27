#----------------------------------------------
#
# Arquivo docker para testes para ubu01
#
#----------------------------------------------

FROM ubuntu:20.04


#Copia arquivos de configuração
COPY    localArquivos/ /tmp/

#Desabilita dialogo no APT
ENV     DEBIAN_FRONTEND noninteractive

##preparando para instalar pacotes
#RUN     apt-get update

##instalacao de servicos
#RUN     apt-get install -y python

##comando de teste
RUN       ls -la 

