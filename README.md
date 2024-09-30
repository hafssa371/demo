TP 1 : Insertion et Récupération des Données avec JDBC

Objectif

Ce projet a pour but de maîtriser l'insertion et la récupération de données dans une base de données MySQL en utilisant Java. Il implémente les API de base de JDBC pour gérer les connexions, les requêtes (statements) et les résultats (result sets), tout en couvrant la gestion des erreurs et les différences entre les packages java.sql et javax.sql.

Prérequis

. Connaissance du langage Java
. NetBeans IDE
. Base de données MySQL (avec la base de données db créée selon les instructions fournies)
. Outils et Bibliothèques
. Java JDK
. Pilote JDBC pour MySQL
. NetBeans IDE
. Aperçu du Projet

Le projet est divisé en quatre parties principales :

Partie 1 : Création du Projet
. Ouvrir NetBeans.
. Aller dans Fichier -> Nouveau Projet.
. Sélectionner Java -> Application Java.
. Donner un nom au projet (par exemple demojdbc) et cliquer sur Terminer.
. Dans les propriétés du projet, ajouter la bibliothèque JDBC pour MySQL.

Partie 2 : Création de la Table
Dans cette partie, nous allons créer une table Site dans la base de données db sous MySQL avec la commande suivante :
![image](https://github.com/user-attachments/assets/0f8bb790-5a79-4f5d-9d10-0a68bf320f42)

Partie 3 : Insertion des Données

1.Créer une classe Site dans le package beans pour représenter les objets Site.
2.Ajouter une méthode save(Site s) pour insérer un site dans la base de données db.
Exemple de code pour l'insertion :
![image](https://github.com/user-attachments/assets/db7893ed-995e-4491-bc9f-cfd82f68ea9e)
![image](https://github.com/user-attachments/assets/88c2e63b-0502-4a5a-b0a6-c5fd6303b0f1)
![image](https://github.com/user-attachments/assets/d52a44e9-a9a7-406a-a9e4-316112885185)
![image](https://github.com/user-attachments/assets/8cf4738e-f4a8-4bc5-83e1-d18890080a6a)

Partie 4 : Récupération des Données

Ajouter une méthode load() pour récupérer et afficher les différents sites stockés dans la base de données.

Exemple de code pour la récupération :
![image](https://github.com/user-attachments/assets/5bfd7acb-699e-47e9-9f17-6841dadff799)
![image](https://github.com/user-attachments/assets/768191e5-1270-41b6-9b7c-2c729d70350e)
![image](https://github.com/user-attachments/assets/1b2288b1-c07d-4937-a1cb-a4c5729cfe1d)
![image](https://github.com/user-attachments/assets/284c6ebd-24bf-4447-a10f-9ed3a12f114e)
![image](https://github.com/user-attachments/assets/693bcd70-fc68-425d-8583-9e90b649d4ed)

Conclusion

Ce projet illustre l'utilisation de l'API JDBC pour manipuler les bases de données à partir de Java. Vous avez appris à insérer et récupérer des données tout en gérant les erreurs possibles et en libérant les ressources après utilisation.









