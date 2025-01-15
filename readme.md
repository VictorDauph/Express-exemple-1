Version Locale

Pour installer les dépendances localement:
npm install

Pour lancer la version locale du projet:
npm start

---------------------------------------------------------------------------
Version conteneur

Pour build une image (avec docker lancé):
docker build -t exemple1 .                                       

Pour lancer une nouvelle instance de l'image (avec nodemon configuré):
docker run -p 3000:3000 -v %cd%:/app -v /app/node_modules exemple1