# Commandes Linux de base

## Shell
Le shell c'est un programme qui va accepter toutes les commandes qu'on va tapé, demandé a l'OS de les lancer, et afficher le resultat sur le terminal
Le terminal c'est la fenêtre, le shell c'est le programme qui tourne a l'intérieur
Le symbole '$' dans enesd@Enes:~/devops-learning/01-linux$ signifie que ton shell est pret a accepter ta commande, $ pour un user, # pour root
Les commande suivent le pattern : command options arguments

## echo
Affiche l texte donnée en argument 

## pwd
Affiche le dossier courant
Sur Linux, tout le filesystem par de '/'. C'est le root et tout les autres dossier sont des subdirectories de '/' 

## ls  
Liste les fichiers
'-a' pour les fichiers cachées (.)
'-l' pour des infos supplémentaires : permissions, taille ...
'-r' pour avoir les fichiers dans l'ordre inverse
'-t' pour trier par date de modification

## cd
Se deplacer a un dossier
'.' represente le repertoire ou on est
'..' represente le repertoire parent
'~' represente le repertoire personnel home (/home/enesd), si on met pas d'arguments, c'est la valeur par défaut
'-' represente le dernier repertoire ou on était
'"Dossier avec espaces"' represente un dossier qui contient des espaces

## touch
Creer un fichier

