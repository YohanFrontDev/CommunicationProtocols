

<!-- Preview = Ctrl + Maj + V -->


# Documentation sur les protocoles de communications.
#### Objectif: Envoyer une requête.
*Pour utiliser un protocole de communication, plusieurs actions sont requises:*


**D'abord, On choisit une méthode :**
```bash

1) Get: Cette méthode récupère des ressources. # exemple: données météo.
2) POST: Cette méthode créer ou modifie une ressource. # exemple: new User
3) PUT: Cette méthode modifie une ressource. # exemple: nom.user de la création POST.
4) DELETE: Cette méthode supprime une ressource. # exemple: des commentaires.

```

*********
**Ensuite, On indique une URL :**
Cette adresse devra correspondre à l'URL que l'on souhaite atteindre.

```bash
# Exemple:
https://github.com/YohanFrontDev/CommunicationProtocols
```


*********


**Puis, nous communiquerons les données voulues :**

```bash
 Les données (page html...)
```
**Une fois que nous aurons effectué ces 3 actions, nous aurons une réponse de la requête:**

```bash
le code HTTP :
	200 : indique que tout s’est bien passé
	400 : indique que votre requête n’est pas conforme à ce qui est attendu
	401 : indique que vous devez être authentifié pour faire cette requête
	403 : indique que vous êtes bien authentifié mais que vous n’êtes pas autorisé à faire cette requête
	404 : indique que la ressource demandée n’existe pas
	500 : indique une erreur avec le service web
```

**À savoir :**

Les mails se font via :
 - le **SMTP** pour l'envoie de mail
 - le **IMAP** pour la réception de mail

Les transfert de fichiers se font via le **FTP**.