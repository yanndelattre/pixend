# Image Node.js
FROM node:18-alpine

# Dossier de travail
WORKDIR /app

# Copier package.json et package-lock.json
COPY package*.json ./

# Installer les dépendances
RUN npm install

# Copier tout le code
COPY . .

# Exposer le port
EXPOSE 3000

# Lancer le serveur
CMD ["npm", "start"]
