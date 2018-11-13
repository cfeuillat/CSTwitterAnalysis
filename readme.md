Attention, ceci n'est pas un repo que vous devez utiliser pour votre projet, juste un tutoriel pour vous aider à config vos projets.

Vous vous inscrivez sur GitHub

Vous créez un nouveau projet `CSTwitterAnalysis`

Si ce n'est pas deja fait vous créez une clef ssh dans votre dossier `~/.ssh` :

	cd ~/.ssh
	ssh-keygen -t rsa

Pas besoin de rentrer de passphrase ni d'email...

Ensuite vous copiez votre clef public (qui peut être affichée avec `cat ~/.ssh/id_rsa.pub`) et vous l'ajoutez comme clef sur votre compte github en utilisant le site web.

En ligne de commande (sur votre console git sous windows ou votre terminal sur Linux/Mac) vous allez dans le dossier de votre projet local s'il existe.

S'il n'existe pas ou que vous voulez refaire tout depuis le début créez un nouveau dossier et faites un `git init` (en ligne de commande) en étant dedans.

Exemple :

	cd C:/mon/projet
	git init

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

	git clone git@github.com:hayj/CSTwitterAnalysis.git






test 3333333 44444
test 3333333 44444