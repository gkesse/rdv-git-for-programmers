#------------------------------------------------
# apprendre git
#------------------------------------------------
# afficher la version
#------------------------------------------------
git --version
#------------------------------------------------
# configurer git
# ouvrir le fichier de configuration
# definir le nom de l'utilisateur <name>
# definir l'adresse email de l'utilisateur <email>
# definir l'editeur de commit <editor>
#------------------------------------------------
git config --global --edit
...
[user]
	name = <prenom nom>
	email = <adresse email>
[http]
	postBuffer = 524288000
	version = HTTP/1.1
[core]
	editor = code --wait
[color]
	ui = true
	status = auto
	branch = auto
[init]
	defaultbranch = master
#------------------------------------------------
# creer un compte sur github
# creer un depot sur github
# recuperer l'url https d'un depot sur github
# cloner un depot
#------------------------------------------------
git clone <url depot>
#------------------------------------------------
# afficher l'etat d'un depot
#------------------------------------------------
git status
#------------------------------------------------
# indexer un dossier
#------------------------------------------------
git add <nom dossier>/
#------------------------------------------------
# indexer un fichier
#------------------------------------------------
git add <nom fichier>
#------------------------------------------------
# valider les modifications avec un message de commit
#------------------------------------------------
git commit -m "<message commit>"
#------------------------------------------------
# indexer tous les fichiers deja suivis
# valider les modifications avec un message de commit
#------------------------------------------------
git commit -am "<message commit>"
#------------------------------------------------
# pousser les modifications
#------------------------------------------------
git push
#------------------------------------------------
# recuperer les modifications
#------------------------------------------------
git pull
#------------------------------------------------
