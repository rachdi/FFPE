# FFPE
      Fin De Projet
    Plateforme Web FFPE



Version : 2.1
Date : 21 Décembre 2016
Lieu: IOT Valley

Auteurs : 

Bassem RACHDI : bigking3100@gmail.com
Christelle TSAGUE : tsagueymele@yahoo.fr
Romain FRECHIC :  romainfrechic@outlook.fr
Rudy  BOKO LENGO : rudy__10@hotmail.fr

Contact : 

Lucette Escudier
ffpe@wanadoo.fr



Introduction
La FFPE(Fédération des Femmes pour l’Europe) est une association participant à la réduction des inégalités femmes-hommes, qui lutte contre les discriminations et toutes formes d’exclusions, encourage l’innovation et relais les orientations et expériences-européennes en faveur de l’égalité des chances.

Lors de notre entrevue l’association FFPE était représentée par Mme Lucette Escudier accompagnée de deux bénévoles.
Il nous a été exposé la problématique suivante : 
“les apprenants des ateliers d’acculturation numérique restent attachés au personnes constitutives du groupe et souhaiteraient profiter des compétences apprises pour tisser des liens entre elles tout en renforçant leurs acquis.”
L’association a porté un intérêt à une création d’une plateforme web permettant la communication et le partage d’informations adaptée au public senior.

L’objectif de ce document est de donner suite à précédente entrevue avec la FFPE à travers un résumé des fonctionnalités un brainstorming avec l’équipe, nous avons constitué des spécifications issues de l’analyse de l’exposé décliné en 3 parties : 
Analyse du besoin, 
Proposition de solution
Compte rendu
Afin d’optimiser le temps de production, nous utiliserons des outils existant sous licence libre qui peuvent être utilisés et modifiés librement, qui ont fait leur preuve car déjà été utilisés et testés par de très nombreux utilisateurs.




Public
Ce public rassemble les caractéristiques suivantes :
Tranche d’âge : de 20 à 99 ans
Résidant en Haute-Garonne
Multilingue: français, anglais, espagnol
Soumis à des problématiques d’accessibilité (problèmes de vision, de motricité, auditifs, de mémoire)
Possiblement peu accoutumés au web

Fonctionnalités
Modérateurs (bénévoles)
Modérer des posts: pouvoir éditer (modifier) un post créé à posteriori (voir annexe 2).
Ajouter/créer des post qui seront vus par les utilisateurs
Bloquer des comptes: si abus du règlement ou publicité de la part d’un utilisateur, le modérateur aura les droits de bloquer le compte pour que l’utilisateur n’ait plus accès à la plateforme.

:
Utilisateurs (séniors)
Consulter les tags sur les posts: voir les ajouts et modifications des modérateurs sur les posts et pouvoir les commenter.
Consulter un calendrier d'actualités: pour que l’utilisateur puisse voir les événements et ses rendez-vous à venir.
Diaspora/Tiki : gestionnaires d'évènements?
Accéder à un chat (rooms, direct, audio/vidéo): pour discuter avec d’autres utilisateurs de l’association par écrit, vocal ou vidéo
Consulter une rubrique d'aides et/ou FAQ et/ou tutoriels: pour apprendre à se servir de la plateforme ou autre selon les tutoriels qui seront postés par les modérateurs.
Contacter les modérateurs de la plateforme: pour avoir davantage d’aide sur l’utilisation de la plateforme ou proposer des améliorations au niveau tutoriel ou aide 
Par mail? via la plateforme?
Accéder à une médiathèque comprenant notamment des ressources vidéos, de la part des modérateurs.
photos…: dépendra du partage des modérateurs, permettra aux utilisateurs de découvrir, s’amuser et s’occuper durant leur temps libre.







Outils
Dans l’optique d’apporter une solution le plus rapidement possible, nous utiliserons les logiciels open-source suivants:

Diaspora: réseau social libre qui permet :
d’échanger des messages et photos avec n'importe quelle autre personne du réseau Diaspora*
de gérer vos contacts, tags, mentions, partages…
de garder le contrôle de vos données
de publier sur d'autres réseaux sociaux (Twitter, Tumblr ou Wordpress)
en somme, d’apprécier toutes les fonctionnalités d'un réseau social sans craindre la censure et dans le respect de votre vie privée
        Installer Diaspora :
         Allées sur le liens du site :
https://wiki.diasporafoundation.org/Installation/Ubuntu/Xenia.
Doc Installation de Diaspora



Tiki Wiki: Permet de créer des bases de connaissances modifiables par les membres de l’association FFPE.
-service en ligne de gestion et de partage de calendriers, qui permet :
de gérer des agendas en ligne, mais aussi vos contacts et vos listes de tâches…
synchronisés entre vos ordinateurs, tablettes, mobiles
Doc Installation de TIKI-WIKI

 Liens github des dossier configurer sass/yml:
               - https://github.com/RomainFrechic/sass-ffpe.git

  
 Organisation :

Définition  du référent
Création de github
Création du Journal de bord quotidien
Utilisation CSS/SASS
Utilisation du Framework CSS de Semantic-ui ?
création du Kanban
Choix d'installation des Outils Diaspora et Tiki en local pour voir si fonctionnalités suffisantes pour le besoin client
choix de créer 2 interfaces de connexion :
Utilisateurs : plus simple
Modérateurs	




  Planned (next thing to do)
Installer Diaspora en local
installer tikiwiki web 
installer ngrok
créer un thème sous diaspora (voir si thème adaptable au besoin ou pas)
docs diaspora(https://diasporafoundation.org/)
Solution alternative ?
modifier la template de diaspora pour l’adapter au    besoin des seniors 
Lecture de la doc pour s’assurer de toutes les fonctionnalités possible des technologies
comments les deux outils peuvent cohabiter?


































Visualisation du projet :
Vidéo Démo




Page d'accueil :



 manuel d'utilisation :

         Modérateurs/Utilisateurs :
Comporte quatre bouton Actus, Agenda, Ressources, Tchat.

Le bouton Actus permet d'accéder via le TikiWiki à une pages
		ou il sera posté par les modérateurs les actualités de l’association FFPE.

Le bouton Agenda permet d'accéder via le TikiWiki à un Agenda.
                       
Le bouton Ressources permet d'accéder via le TikiWiki à une page
                       ou il sera posté par les modérateurs les ressources, tutos 
                       de l’association FFPE. 






Réseau Social avec Diaspora :




manuel d'utilisation :

    Les Modérateurs :

Modérer des posts: pouvoir éditer (modifier) un post créé à posteriori .

Ajouter/créer des post qui seront vus par les utilisateurs

Bloquer des comptes: si abus du règlement ou publicité de la part d’un utilisateur, le modérateur aura les droits de bloquer le compte pour que l’utilisateur n’ait plus accès à la plateforme.

Les Utilisateurs :

Consulter les tags sur les posts: voir les ajouts et modifications des modérateurs sur les posts et pouvoir les commenter.

Accéder à un chat : pour discuter avec d’autres utilisateurs de l’association par écrit, vocal ou vidéo.

pouvoir éditer (modifier) un post créé à posteriori .


Calendrier Avec TikiWiki :




manuel d'utilisation :

    Les Modérateurs :

Ajouter/créer/supprimer des évènements qui seront vus par les utilisateurs.


    Les Utilisateurs :

Consulter un calendrier d'actualités: pour que l’utilisateur puisse voir les événements et ses rendez-vous à venir.














Ressources avec TikiWiki : 





manuel d'utilisation :

    Les Modérateurs :

Ajouter/créer/supprimer des Ressources/tutos qui seront vus par les utilisateurs.


    Les Utilisateurs :

Consulter les Ressources/tutos d'actualités: pour que l’utilisateur puisse voir les événements et ses rendez-vous à venir.






