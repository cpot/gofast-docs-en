================================
GoFAST Community : Configuration
================================

.. figure:: /media-guide/Logo-Community.png
   :alt: 

.. NOTE:: Afin de pouvoir configurer votre GoFAST Community, vous devez tout d'abord vous rendre sur l'adresse IP correspondant à votre serveur (sur lequel vous avez instancié GoFAST). 
Example : http://35.180.66.5

Pour finaliser la configuration de votre GoFAST Community, 5 étapes sont requises : 

  - Change name domaine
  - Configure SSL Certificate
  - Configure SMTP Server
  - Create Admin User
  - Finish Configuration 

Ci-après nous allons détailler chaque étape de cette configuration et en quoi correspond les différents champs demandés. 


Etape 1 : Change Name Domain 
-------------------

L'écran de configuration de l'étape 1 est représenté comme ci-dessous : 

.. figure:: /media-guide/Change-Name-Domaine.png 

Sur cet écran vous devez remplir plusieurs champs avant de passer à l'étape suivante : 

1. **New Sub-Domain** : ce premier champs va correspondre au nom présenté avant votre nom de domaine dans l'URL de votre GoFAST Community
2. **New Domain** : ce second champs va venir se positionner après le sub-domain dans l'URL. Généralement les entreprises suggère le nom de leur enseigne. 
3. **New extension** : vous avez la possibilité de choisir l'extension de votre choix (.com, .fr, .es, .org, ...) 

Cette étape va correspondre à la configuration de votre URL pour accéder à votre GoFAST en Full Web par la suite. 


Etape 2 : Configure SSL Certificate 
-----------------------------------

Dans cette étape vous avez deux possibilités de créer votre certificat SSL de sécurité.

.. figure:: /media-guide/Configure-SSL-1.png 
   :alt: 

La première option va vous demander de télécharger vos certificats, afin de pouvoir utiliser votre propre Certificat SSL :
- **Key Private** :  
- **Key Public** : 

La deuxième option va vous permettre de créer votre certificat de sécurité SSL en même temps que la configuration de votre GoFAST Community. 
Plusieurs champs vont vous être demander pour la configurer, voir copie d'écran ci-dessous.

Ces champs sont obligatoires pour configurer votre certificat SSL

.. figure:: /media-guide/Configure-SSL-1-modified.png 
   :alt:
   
.. figure:: /media-guide/Configure-SSL-Certificate-2.png
   :alt: 
      
1. **Country**
2. **State or Province**
3. **City**
4. **Company** 
5. **Organization unit** : Correspond à votre département 
6. **Web site name**
7. **E-mail address** 



Etape 3 : Configure SMTP Server 
-------------------------------

La troisième étape dans la configuration de votre GoFAST Community concerne la configuration dans votre serveur de la plateforme 

.. figure:: /media-guide/Configure-SMTP-1.png
   :alt:
   
.. figure:: /media-guide/Configure-SMTP-2.png
   :alt: 
   
Les différents champs demandés correspondent à : 

   1. **SMTP Server** :  
   2. **Username** : 
   3. **Password** : 
   4. **Security** : None (without security), TLS (....), SSL (....)
   5. **SMTP Port** : 
   6. **Recipient address** : 


Etape 4 : Create Admin User
---------------------------

La troisième étape correspond au compte utilisateur "administrateur" qui permettra les différents paramétrages sur votre GoFAST Community. 

Vous allez alors devoir choisir un login, password, 

.. figure:: /media-guide/Create-Admin-User-1.png
   :alt:
   
.. figure:: /media-guide/Create-Admin-User-2.png
   :alt:



Etape 5 : Finish Configuration 
------------------------------

Cette dernière étape est une synthèse de toutes les informations que vous avez rempli préalablament avant la configuration finale de votre GoFAST Community 

.. WARNING :: Attention, après avoir cliqué sur le bouton "Finish Configuration" vous ne pourrez plus retourner sur les étapes précédéentes. Il est alors important de devoir vérifier tous les champs que vous avez rempli préalablement. 

.. figure:: /media-guide/Finish-Configuration-Community.png
   :alt: 
   


   
