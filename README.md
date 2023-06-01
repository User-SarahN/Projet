## Projet Darties
Ce projet a été conçu pour créer un tableau de bord interactif sur Power BI et traiter et nettoyer les données à l'aide de Talend. L'utilisateur peut accéder facilement au tableau de bord via un site Internet convivial.

## Prérequis
Avant de pouvoir accéder au site et profiter pleinement du tableau de bord, assurez-vous d'avoir les éléments suivants installés sur votre ordinateur :

- XAMPP : Une suite logicielle comprenant Apache, MySQL, PHP, etc., pour héberger le site localement.
- Power BI : Un logiciel de visualisation des données.
- Talend version 8.0.1 : Un outil d'intégration et d'analyse des données.

De plus, pour faciliter le traitement et le nettoyage des données dans Talend, un exécutable Python a été développé. Assurez-vous d'avoir Python installé sur votre machine.

## Installation
Suivez ces étapes pour installer et configurer le projet sur votre machine :

1. Téléchargez et installez XAMPP à partir du lien suivant : https://www.apachefriends.org/fr/download.html
2. Téléchargez le fichier "Site AMOA.zip" et décompressez-le.
3. Localisez le répertoire d'installation de XAMPP sur votre ordinateur (par exemple, "C:\xampp\htdocs").
4. Copiez les fichiers extraits ("dashboard_role.php", "index.php", "style.css" et "darties_logo.png") dans le répertoire "C:\xampp\htdocs".
5. Assurez-vous que XAMPP est en cours d'exécution et démarrez Apache et MySQL.
6. Ouvrez votre navigateur Web et entrez l'URL suivante : http://localhost/index.php.

## Utilisation de l'exécutable Python
Pour faciliter le traitement et le nettoyage des données dans Talend, un exécutable Python a été développé. Voici comment l'utiliser :
1. Assurez-vous d'avoir Python installé sur votre machine.
2. Accédez au répertoire où se trouve le fichier exécutable Python et vos données (Projet AMOA/Talend/Executable/).
3. Lancer l'executable "Update_mensuel.exe"
4. Séléctionner le dossier contenant vos fichiers contenant vos données (Projet AMOA/Data)
5. Valider votre sélection
![image1](1.png)

L'exécutable Python lancera automatiquement les jobs Talend en utilisant les données fournies. Suivez ces instructions afin de démarrer le processus de traitement et de nettoyage des données pour les nouvelles entrées entrantes.

## Connexion au tableau de bord
Une fois sur la page d'accueil du site (http://localhost/index.php), vous serez invité à vous connecter pour accéder à votre tableau de bord personnalisé. Utilisez les informations de connexion suivantes :
- Utilisateur : (Les identifiants sont disponibles dans le document "users.xlsx")
-  Mot de passe : (Les mots de passe correspondants sont également disponibles dans le document "users.xlsx")
Une fois connecté, vous pourrez explorer les données et interagir avec le tableau de bord Power BI.
![image1](2.png)

## Remarque
Assurez-vous d'avoir des autorisations suffisantes pour accéder au site, aux fichiers nécessaires et pour exécuter des scripts Python sur votre machine. En cas de problème lors de l'installation ou de l'utilisation du tableau de bord, veuillez consulter la documentation fournie avec les logiciels XAMPP, Power BI et Talend, ainsi que les ressources en ligne correspondantes, pour obtenir de l'aide supplémentaire.

## Conseils
Profitez de votre expérience avec le projet Darties et n'hésitez pas à partager vos commentaires et suggestions pour son amélioration ! 

## Contacts
Pour toutes questions relatives au projet n'hésitez pas à nous contacter à l'adresse mail suivante : sarah.nait-atmane@etu.univ-lyon1.fr



## Aperçu de quelques pages du dashbaord 
![image1](3.png)
![image1](4.png)
![image1](5.png)
![image1](6.png)
![image1](7.png)
![image1](8.png)
