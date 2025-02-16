FROM node:16.13.2
WORKDIR /app
COPY package*.json ./
# Essa copia é feita para evitar que mudanças simples no código
# façam com que todos os pacotes sejam instalados sempre
RUN npm install
COPY . .
CMD ["node", "server.js"]