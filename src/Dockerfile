#interesante colocar a tag 
FROM node:16.14.0
#cria um dir app
WORKDIR /app
#copia ambos os packagr, por isso do *
COPY package*.json ./
#instala o npm
RUN npm install
#copia tudo
COPY . .
#inicializa a aplicacao 
CMD ["node", "server.js"]   