Gestionnaire de Tâches
Le projet Gestionnaire de Tâches est une application web simple conçue pour aider les utilisateurs à organiser et gérer leurs tâches efficacement. Inspiré par la flexibilité et la polyvalence de Notion, ce projet vise à fournir aux utilisateurs une expérience de gestion des tâches rationalisée avec des fonctionnalités telles que la création de tâches, la catégorisation, la priorisation et le suivi.

Fonctionnalités
Création de Tâches: Les utilisateurs peuvent facilement créer de nouvelles tâches, en spécifiant des détails tels que le titre, la description, la date d'échéance et la priorité.

Gestion de Catégories: Les tâches peuvent être organisées dans différentes catégories ou projets, permettant aux utilisateurs de regrouper les tâches connexes pour une meilleure organisation et clarté.

Attribution de Priorité: Les utilisateurs peuvent attribuer des niveaux de priorité aux tâches, les aidant à identifier et à se concentrer sur les tâches prioritaires de manière plus efficace.

Suivi des Tâches: L'application fournit aux utilisateurs un tableau de bord centralisé pour afficher toutes leurs tâches, suivre leur progression et surveiller les prochaines échéances.

Interface Conviviale: Avec une interface utilisateur propre et intuitive, le Gestionnaire de Tâches garantit une expérience utilisateur agréable, rendant la gestion des tâches simple et efficace.

Technologies Utilisées
Frontend: HTML,Tailwind CSS

Backend: Framework Laravel Blade

Base de Données: Base de données MySQL pour stocker les données des tâches

Authentification: Laravel Passport pour l'authentification et l'autorisation des utilisateurs

Déploiement: Conteneurs Docker pour un déploiement et une évolutivité faciles

Pour commencer avec le projet Gestionnaire de Tâches, suivez ces étapes :

Cloner le Dépôt: Clonez le dépôt du Gestionnaire de Tâches sur votre machine locale en utilisant la commande suivante :

bash
Copy code
git clone https://github.com/votre-nom-utilisateur/gestionnaire-de-taches.git
Installer les Dépendances: Accédez au répertoire du projet et installez les dépendances nécessaires à l'aide de Composer et npm :

bash
Copy code
cd gestionnaire-de-taches
composer install
npm install
Configuration de la Base de Données: Configurez les paramètres de votre base de données dans le fichier .env et exécutez les migrations de base de données pour créer les tables nécessaires :

bash
Copy code
php artisan migrate
Démarrer le Serveur de Développement: Lancez le serveur de développement Laravel pour démarrer l'application :

bash
Copy code
php artisan serve
Accéder à l'Application: Ouvrez votre navigateur web et accédez à http://localhost:8000 pour accéder à l'application Gestionnaire de Tâches.

Contribution
Les contributions sont les bienvenues ! Si vous souhaitez contribuer au projet Gestionnaire de Tâches, veuillez forker le dépôt, apporter vos modifications et soumettre une demande de fusion (pull request). Assurez-vous de suivre les normes de codage et les directives du projet.