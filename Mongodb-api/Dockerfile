# Utilise une image Node.js officielle
FROM node:18

# Dossier de travail
WORKDIR /app

# Copie les fichiers de dépendances
COPY package*.json ./

# Installe les dépendances
RUN npm install

# Copie le reste de l'application
COPY . .

# Expose le port
EXPOSE 3000

# Commande pour lancer le serveur
CMD ["npm", "start"]
