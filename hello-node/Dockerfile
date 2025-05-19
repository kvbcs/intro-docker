#Etape 1 : image de base
FROM node:18
#Etape 2 : création d'un dossier de travail
WORKDIR /app
#Etape 3 : copier les fichiers de dépendances
COPY package.json .
#Etape 4 : installer les dépendances
RUN npm install
#Etape 5 : copier le code source vers l'image
COPY app.js .
#Etpae 6 : exposer le port utilisé par l'app
EXPOSE 3000
#Etape 7 : commande de lancement
CMD ["npm", "start"]