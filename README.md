Gestionnaire de Patients d'Hôpital

- Introduction

Le Gestionnaire de Patients d'Hôpital est une application web JEE conçue pour aider le personnel hospitalier à gérer les dossiers des patients. Il fournit une interface conviviale qui permet au personnel de créer, mettre à jour et supprimer des dossiers de patients, de planifier des rendez-vous et de gérer les antécédents médicaux.

//////////////////////////////////////////////////////////

- Fonctionnalités:

- Création, mise à jour et suppression de dossiers de patients
- Planification de rendez-vous
- Gestion des antécédents médicaux
- Recherche de patients par nom, ID ou autres informations
- Système de connexion sécurisé

//////////////////////////////////////////////////////////

- Technologies utilisées:

- Maven pour la gestion des dépendances
- Base de données MySQL
- JEE
- Spring Framework
- Hibernate ORM (Object Relational Mapping)
- Bootstrap pour la conception de la partie frontale

//////////////////////////////////////////////////////////


Installation

1. Clonez ce référentiel en utilisant `git clone https://github.com/MOU1D/Patient_Proj.git`.
2. Importez le projet dans votre IDE (Eclipse, IntelliJ, etc.) en tant que projet Maven.
3. Configurez la connexion à la base de données dans le fichier `application.properties` situé dans le dossier `src/main/resources`.
4. Construisez et exécutez l'application en utilisant la commande `mvn clean package` pour construire le fichier WAR et le déployer sur un serveur Tomcat.

//////////////////////////////////////////////////////////


  Utilisation

1. Après avoir démarré l'application, ouvrez un navigateur Web et allez à l'adresse `http://localhost:8080/hospital-management/`.
2. Utilisez les identifiants de connexion par défaut pour accéder au tableau de bord :
   - Nom d'utilisateur : admin
   - Mot de passe : 1234
3. Depuis le tableau de bord, le personnel hospitalier peut gérer les dossiers des patients, planifier des rendez-vous et consulter les antécédents médicaux.

//////////////////////////////////////////////////////////


 Contributors

This project was created by [MOU1D](https://github.com/MOU1D). Contributions are welcome and appreciated.
