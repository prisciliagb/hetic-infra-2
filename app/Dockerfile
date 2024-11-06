# Utilisez une image de base Node.js
FROM node:14


# Copier le fichier package.json et installer les dépendances
COPY package*.json ./
RUN npm install

# Copier le reste du code
COPY app.js .

COPY public .

COPY routes/route.js .

COPY views/home.ejs .


# Exposer le port
EXPOSE 3000

# Commande pour lancer l'application
CMD ["npm", "start"]

