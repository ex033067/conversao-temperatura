FROM node:18.11.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]

# Para criar a imagem:
# $ docker image build -t ex033067/conversao-temperatura:v1
#
# Para rodar o container a partir da image criada acima:
# $ docker run --rm -d -p 8080:8080 ex033067/conversao-temperatura:v1
#
# Link para a imagem no Docker Hub: https://hub.docker.com/repository/docker/ex033067/conversao-temperatura/general
