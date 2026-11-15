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

## file
Identifie le contenue d'un fichier, car sur linux un fichier peut s'apeller "images.jpg" et ne pas etre un jpg. btw c'est une classification, pas une garantie
'-i' pour afficher les MIME infos

## cat
Afficher le contenu d'un fichier
'text1 text2 > text3' : va ecrire le contenue de text1 et ensuite de text2 dans text3
'> text4' : Interessant aussi quand tu veux écrire un entrée du terminal dans un fichier; ctrl+D pour arreter l'enregistrement du terminal
'>> text4' : Si tu veut rajouter du texte a la suite sans écraser le fichier. Marche aussi avec un fichier en entrée
Privilégié less pour les fichiers longs

## less
Affiche le contenue d'un fichier, préférable pour les longs fichiers
relou a utilisé, q pour quitter

## history
Retrace l'historique des commandes envoyé
!! pour lancer la derniere commande (ou fleche du haut)
!100 pour lancer la 100eme commande qu'on avait tapé
!cat pour lancer le dernier cat qu'on avait lancé, si t'avais lancé cat text3 ca va lancer celui la.
ctrl + r pour faire une recherche sur le nom de la commande qu'on veut, du plus récent au plus ancien, ctrl r pour remonter a un match plus ancien

## clear
Pour avoir un terminal propre, on voit plus les anciennes sorties de commandes

## cp
Copier un fichier dans un fichier ou dossier
avec -r tu peux copier recursivement un dossier dans un dossier
'-i' pour qu'on te demande avant de modifier un fichier existant
'-n' pour qu'on t'interdit de modifier un fichier existant
'-p' pour garder les modes, propriétaire, et timestamp quand possible

## mv
Renommer ou Deplacer un fichier ou un dossier d'endroit

## mkdir
Créer un dossier

