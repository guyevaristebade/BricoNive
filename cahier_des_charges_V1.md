# Cahier des charges fonctionnelles pour l'application "ToolHub"

## 1. Introduction

    1.1 Objectif du document
    
    Le présent document a pour objectif de définir les fonctionnalités et les exigences fonctionnelles de l'application "ToolHub ou BricoNive".

    1.2 Contexte du projet

    "ToolHub ou BricoNive" est une application web destinée à aider les utilisateurs à gérer et suivre leurs outils, enregistrant les informations sur les prêts et facilitant le partage entre utilisateurs.

## 2. Fonctionnalités de base

    2.1 Répertoire d'outils

    Enregistrement des outils avec les détails suivants : nom, catégorie, emplacement, description, image.
    Affichage des outils répertoriés avec la possibilité de recherche, filtrage par catégorie et tri par emplacement.

    2.2 Gestion des prêts

    Possibilité de prêter des outils à d'autres utilisateurs enregistrés.
    Enregistrement des prêts avec les détails suivants : utilisateur / emprunteur, date de début du prêt, date de retour prévue.
    Notifications pour rappeler les retours imminents.
    Historique des prêts en cours et passés.

    2.3 Visualisation des caractéristiques des outils

    Affichage des détails complets de chaque outil, y compris l'image, pour une référence visuelle.

    2.4 Formulaire d'enregistrement

    Formulaire convivial pour l'ajout d'un nouvel outil avec téléchargement d'image.

    2.5 Communication entre les particulier 

    Possibilité de joindre un emprunteurs par message 

    2.6 Système d'authentification

    Inscription avec nom, prenom, adresse e-mail et mot de passe.

    Connexion sécurisée avec gestion des sessions.



## 3. Technologies

    3.1 Frontend

    Utilisation de React.js pour une interface utilisateur réactive et dynamique.

    3.2 Backend

    Node.js avec Express pour la gestion du backend.

    3.3 Base de données

    MongoDB pour le stockage des informations sur les outils, les prêts et les utilisateurs.

    3.4 Authentification

    JWT (JSON Web Tokens) pour assurer un accès sécurisé.

## 4. Contraintes et Recommandations

    Respect des lois et normes de protection des données personnelles.
    Interface utilisateur conviviale et responsive.

    Tests rigoureux pour assurer la stabilité et la sécurité de l'application.

    Documentation détaillée du code pour faciliter la maintenance.


## 5. Conclusion

    Le cahier des charges fonctionnelles "ToolHub" vise à établir une base solide pour le développement de l'application. 
    
    Il est sujet à des évolutions en fonction des besoins et des retours des utilisateurs. 
    
    Toute modification substantielle sera documentée et validée par l'équipe de développement.


Version 1.0 - 21 Décembre 2023