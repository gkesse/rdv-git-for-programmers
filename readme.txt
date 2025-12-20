#------------------------------------------------
# apprendre git
#------------------------------------------------
# afficher la version
#------------------------------------------------
git --version
#------------------------------------------------
# ouvrir le fichier de configuration
# configurer git
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
# valider les modifications avec un message de commit
#------------------------------------------------
git commit -m "<message commit>"
#------------------------------------------------
# pousser les modifications
#------------------------------------------------
git push
#------------------------------------------------
