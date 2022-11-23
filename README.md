# website de code-source-pro

# DEPENDANCE AVANT DE DEMARRER L'APPLIACTION
  
  Il faut s'assurer que la version du php que tu disposes est entre: 7.0 et 8.0
  et La version de Laravel est 8. Sinon il aura cache.


# Comment installer ce projet en local?
  # Les étapes à suivre:
  1- Cloner notre repository à l'aide du terminal gitbash: git clone https://github.com/Code-source-Pro/website.git
  2- Faire pour entrer dans le dossier: cd website
  3- Installer les dépendances du projet à partir de composer:
     -Faire (s'assuré composer deja installé): composer install
     -Faire (s'assuré Nodejs deja installé): npm install
  4-Créer une copie de votre fichier .env : cp .env.example .env
  5- Générez votre clé d’encryption : php artisan key:generate
  6- Quelques commandes pratiques (Optionnel) :
     Nettoyer votre projet :
    . php artisan cache:clear
    . php artisan view:clear
    . php artisan config:clear
  7- Créer une base de donnée vide pour votre projet:

  Nous voudrons permettre à Laravel de se connecter à la base de données que vous venez de créer à l’étape précédente. Pour ce faire, nous devons ajouter les références de connexion dans le fichier .env et Laravel se chargera de la connexion à partir de là.

  Dans le fichier .env, remplissez les options DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME et DB_PASSWORD pour qu’elles correspondent aux informations d’identification de la base de données que vous venez de créer. 

8- Ajouter les tables et contenus de votre base de donnée avec les migrations ou en sql
taper: php artisan migrate,
       php artisan db:seed
       php artisan migrate:fresh --seed
9- Demarrer le projet en tapant dans la ligne de commande: php artisan serve,


Cependant, il ya des donner par defaut qui son sont dejà predefini que j'ai.
 



