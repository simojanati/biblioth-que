# biblioth-que
====================CONCEPTION ET REALISATION D’UN SYSTEME SUPPORT POUR UNE BIBLIOTHEQUE=================
L'application a été réalisée en Java (Swing) avec L'IDE  NetBeans 8.1 et le SGBD MARIA DB
Il faut donc ces deux logiciels : 
1-Télécharger et installer NetBeans 8.1 
2-Télécharger et installer Maria DB
3-Importer le projet "Bibal_Janati_Diallo_Code_Netbeans" dans NetBeans
4-Un script de création des tables la base de données avec des données de test se trouve dans
 le projet importé dans NetBeans : package Utility/Bibal_Janati_Diallo.sql
5-Ajouter le driver de Maria DB (Par defaut nous l'avons ajouté)
6-Dans le package Utility se trouve le fichier de configuraton de la base de   données qui se nomme DatabaseConfig.properties il faut changer les variables : 
	SGBD.URL par le nom de la base 
	SGBD.DRIVER par le nom du driver (qui devrait normalement pas être changé)
	SGBD.USER par le nom d'utilisateur
	SGBD.PASSWORD par le mot de passe de l'utilisateur
7-Après ces configurations on peut maintenant lancé l'application
