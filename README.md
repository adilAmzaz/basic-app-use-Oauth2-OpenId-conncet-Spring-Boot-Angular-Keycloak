# basic-app-uses-Oauth2-OpenId-conncet-Spring-Boot-Angular-Keycloak
Cette application web est une application basic qui contient trois pages�en mode hors ligne: page d�accueil, page d�inscription et page de connexion. En mode en ligne une page qui affiche toutes les utilisateurs dans le cas d�un utilisateur admin s�ajoute.
L�application s�int�resse surtout � utiliser le protocole oauthe2 et OpenId connect, le but au d�but a �t� d�utiliser Spring Security pour permettre �a, mais vu que le developpement va s�arr�ter pour ce protocole par la communaut� Spring, parmi les solutions les plus r�put�s et alternatives est Keycloak. Pour permettre aux utilisateurs de se connecter en  mode s�curis� utilise les technologies suivantes�:

## Technologies:
- Spring Boot 2.3
- Spring Security 
- Angular 9.0
- Keycloak 10.0
- Spring Data JPA
- Mysql 8.0

L�application a la particularit� d�utiliser une base de donn�e externe en utilisant Keycloak user storage provider (plus de details dans le projet����), le front le moment de l�inscription permet le stockage des donn�es d�utilisateur dans cette base externe, Keycloak user Storage provider permet la r�cup�ration et la v�rification des donn�es pour permettre l�authentification.


