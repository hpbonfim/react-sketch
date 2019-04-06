FROM node:latest

#1º montar um diretorio central do aplicativo
WORKDIR /src

#2º copiar todos os arquivos do app para o Docker
COPY . ./

#3º instalar os repositorios no docker
RUN yarn install

# configurar cache-clean
# RUN yarn cache-clean

#4º start Server
RUN cd /src/ yarn start



