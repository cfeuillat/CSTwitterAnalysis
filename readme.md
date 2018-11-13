Attention, ceci n'est pas un repo que vous devez utiliser pour votre projet, juste un tutoriel pour vous aider à config vos projets.

Vous vous inscrivez sur GitHub

Vous créez un nouveau projet `CSTwitterAnalysis`

En ligne de commande (sur votre console git sous windows ou votre terminal sur Linux/Mac) vous allez dans le dossier de votre projet local s'il existe.

S'il n'existe pas ou que vous voulez refaire tout depuis le début créez un nouveau dossier et faites un `git init` en étant dedans

Ensuite vous ajoutez le repo sur les serveurs github (remplacez "hayj" par votre username) :

	git remote add origin git@github.com:hayj/CSTwitterAnalysis.git

Si cela ne marche pas c'est que vous avez deja un remote donc vous devez le changer avec :

	git remote set-url origin git@github.com:hayj/CSTwitterAnalysis.git

Si ce n'est pas deja fait vous faites le premier commit :
	
	git add . ; git commit -m "minor update"

Ensuite vous faites le premier push:

	git push -u origin master

Vous invitez votre binome dans le projet sur le site web GitHub.

Votre binome doit faire un clone sur son pc :

	git@github.com:hayj/CSTwitterAnalysis.git