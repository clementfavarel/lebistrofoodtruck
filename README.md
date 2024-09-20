# Le Bistro Foodtruck App

## Description
Le Bistro Foodtruck App est une application web vitrine et responsive pour Le Bistro Foodtruck.<br>
Elle permet aux utilisateurs de consulter le menu, les services proposés, ainsi que de gérer leur compte fidélité.<br>
Accessible via un navigateur, cette application vise à augmenter la visibilité du foodtruck et à offrir une expérience utilisateur fluide sur tous les appareils.

## Features
- Page d'accueil vitrine
- Menu
- Système de fidélité utilisateur avec compte
- Notifications push
- Responsive design
- Tableau de bord administrateur

## Technologies utilisées
- **Framework** : Laravel 11
- **Starter Kit** : Breeze
- **Base de données** : MariaDB
- **Contrôle de version** : Git
- **Développement en conteneur** : Distrobox

## Installation

Pour installer et lancer l'application localement :

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/clementfavarel/le-bistro-foodtruck-app.git
   cd le-bistro-foodtruck/src
   ```

2. Installez les dépendances PHP avec Composer :
   ```bash
   composer install
   ```

3. Installez les dépendances JavaScript avec NPM :
   ```bash
   npm install
   ```

4. Copiez le fichier .env.example en .env et modifiez-le si nécessaire :
   ```bash
   cp .env.example .env
   ```

5. Générez la clé de l'application :
   ```bash
   php artisan key:generate
   ```

6. Lancez les migrations et les seeders pour peupler la base de données :
   ```bash
   php artisan migrate --seed
   ```

## Utilisation

L'application est accessible via un navigateur.<br>
Une fois installée, les utilisateurs peuvent consulter l'application en se rendant à l'URL définie dans le fichier .env.<br>
Ils pourront parcourir le menu, créer un compte pour accumuler des points de fidélité, et recevoir des notifications sur les nouveautés du foodtruck.

## Contributions

Les contributions ne sont pas encore ouvertes.

## License

Ce projet ne dispose pas d'une license spécifique pour le moment.

## Contact

Pour toute question ou support, vous pouvez nous contacter via :

GitHub : [clementfavarel](https://github.com/clementfavarel)

Email : [info@lebistrofoodtruck.co.at](info@lebistrofoodtruck.co.at)