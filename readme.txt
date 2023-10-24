Ce fichier est crée manuellement par MEHDI le 04/05/2020 à 09:19
**************************************************TEST******************************
--Client Angular tester_locale_HN-Quiz-UI
Pour tester le QUIZ en locale il faut ouvrir cmd et exécuter les étapes suivantes: 
 
1-cd C:\Users\mchaabani\Desktop\eclipse-jee-mars-2-win32-x86_64\workspaceHN\HN-Quiz\HN-Quiz-UI
2-ng serve
3-http://localhost:4200



--Serveur HN-Quiz-Service (coté java)
Pour tester le QUIZ en locale il faut ouvrir eclipse et exécuter les étapes suivantes: 
 
1-Entrer dans AppNameApplication.java
2-bouton droit -> Run As ->Java Application



********************************************PROD*************************************
pour déployer le QUIZ en production, il faut : 

0-Clean and install HN-Quiz-UI (bouton droit dans pom.xml --> Run As -->Maven Clean --> Maven Install)
1-Générer un ficher .jar de projet par le fichier pom.xml de HN-Quiz-Service
2-Déposer le fichier jar dans n'importe quel endroit et faire double clic sur ce jar
3-Ouvrir le navigateur et tapper http://localhost:8080

et comme ça on aura le projet qui tourne en mode production
