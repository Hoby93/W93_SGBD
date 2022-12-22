> LANCEMENT :
	(1) A-CServer.bat (lancer le serveur)
	(2) B-CServer.bat (lancer un client)
	
> SYNTAXE DE BASE :
	(1) Creation DataBase.
		- CREATE DATABASE DBName

	(2) Voir DataBase(s)
		- SHOW DATABASE

	(3) Utilisation DataBase
		- USE DBName

	(4) Creation Table
		- CREATE TABLE TName (C1,C2,C3,...,Cn)

	(5) Voir Table(s)
		- SHOW TABLE

	(6) Modification dans une Table
		- UPDATE TName SET C1=X1,C2=X2,...,Cn=Xn WHERE C1=W1 AND/OR ... AND/OR Cn=Wn

	(7) Suppression dans une Table
		- DELETE TName WHERE C1=W1 AND/OR ... AND/OR Cn=Wn

	(8) Projection Simple :
		-  SELECT C1,...,Cn FROM TName

	(9) Projection avec Selection (Multiple)
		-  SELECT C1,...,Cn FROM TName WHERE C1=W1 AND/OR ... AND/OR Cn=Wn

	(10) Projection avec Jointure (02 Tables seulement)
		-  SELECT C1,...,Cn FROM T1Name JOIN T2Name On T1C=T2C (Jointure)

	(11) Projection avec plusieurs sous-requettes
		-  SELECT C1,...,Cn FROM (sous-requette)

	(12) Deconnexion
		- QUIT

> NB:
	- Les nom des Tables et Colonnes ne sont pas sensibles a la case
	- Les donnes sont sensibles a la case
	- Pas de ';' apres chaque requette
	- '*' pour designer tout les colonnes
	- Une sous-requette peut contenir d'autre sous-requette
	- Vous pouvez lancer plusieurs clients (Multi-thread)

@ETU001839