
Vous vous inscrivez sur GitHub
Vous créez un nouveau projet

En ligne de commande vous allez dans le dossier de votre projet local

Si ce n'est pas deja fait vous faites le `git init`

Ensuite vous ajoutez le repo sur les serveurs github (remplacez "hayj" par votre username) :

	git remote add origin git@github.com:hayj/CSTwitterAnalysis.git

Si ce n'est pas deja fait vous faites le premier commit :
	
	git add . ; git commit -m "minor update"

Ensuite vous faites le premier push:

	git push -u origin master