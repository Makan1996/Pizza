# Pizza
Ce programme permet la connexion à une base de données my SQL qui permet d'extraire et d'afficher les données d'une pizzeria

Description : 

Ce projet Java permet la connexion à une base de données MySQL afin d'extraire et d'afficher des données issues de différentes tables : CLIENT, LIVREUR et PIZZA. Chaque classe Java correspond à une table spécifique et exécute une requête SQL pour récupérer les informations.

Prérequis :

-Java (JDK 8 ou supérieur)
-MySQL Server
-JDBC Driver MySQL (mysql-connector-java)
-Un environnement de développement (Eclipse, IntelliJ, NetBeans, etc.)

Installation et Configuration :

-Téléchargez et installez MySQL Server.
-Créez la base de données pizzaboxinnodb avec les tables nécessaires (CLIENT, LIVREUR, PIZZA).
-Ajoutez le connecteur JDBC (mysql-connector-java.jar) à votre projet.
-Vérifiez et ajustez les identifiants de connexion dans chaque classe (login, password, url).

Explication des Classes :

1. Client_connect.java
-Se connecte à MySQL.
-Exécute la requête : SELECT * FROM CLIENT.
-Affiche les colonnes NOMCLIE, PRENOMCLIE, ADRESSECLIE.
2. Livreur_connect.java
-Se connecte à MySQL.
-Exécute la requête : SELECT * FROM LIVREUR.
-Affiche les colonnes NOMLIVR, PRENOMLIVR, DATEEMBAUCHLIVR.
3. Pizza_connect2.java
-Se connecte à MySQL.
-Exécute la requête : SELECT * FROM PIZZA.
-Affiche les colonnes DESIGNPIZZ, TARIFPIZZ, NROPIZZ, image1_chemin.

Problèmes Possibles et Solutions :

-Erreur de connexion à MySQL : Vérifiez l'URL, le login et le mot de passe.
-Driver JDBC non trouvé : Assurez-vous que mysql-connector-java.jar est bien ajouté au classpath.
-Table inexistante : Vérifiez que votre base de données et ses tables sont correctement créées.

Auteur :

Développé par MAKAN NJOBEN Jordan.

Licence :

Projet open-source sous licence MIT.
