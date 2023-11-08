# **Définition générale**

_Lazygit_ est une **interface utilisateur** permettant de lancer des commandes Git dans le Terminal sans utiliser de ligne de commande.

_Lazygit_ permet globalement d'ajouter des fichiers à un projet, résoudre des conflits avec des merges, réaliser des checkout rapides, parcourir des logs et réaliser des push, pull ou encore renommer des commits.

![Interface Lazygit](https://blog.sasworkshops.com/content/images/wordpress/2021/02/image_2021-02-02_095617.png)

## Commandes de lazygit

Voici quelques-unes des opérations et commandes courantes dans LazyGit :

### Commandes globales :

* ```Esc``` : Quitter/Annuler
* ```Enter``` : Confirmer/Valider
* ```PageUP``` / ```PageDown``` : Défiler sur les panels
* ```Ctrl + R``` : Retour sur le repo le plus récent
* ```@``` : Menu des commandes de connexion
* ```?``` : Menu principal
* ```Z``` : Annuler la dernière commande
* ```Ctrl + Z``` : Refaire la commande annulée précédemment
* ```Shift + P``` : Faire un _Push_
* ```P``` : Faire un _Pull_

### Navigation :

* ```,``` : Page précédente
* ```.``` : Page suivante
* ```<``` ou ```>``` : Défiler tout en haut ou tout en bas
* ```H``` ou ```L``` : Défiler tout à gauche ou tout à droite

### Fichier Commit :

* ```O``` : Ouvrir un fichier
* ```E``` : Editer un fichier
* ```Ctrl + O``` : Copier le nom du commit sur le clipboard
* ```Espace``` : Basculer le fichier en correction
* ```A``` : Basculer tous les fichiers en correction

### Commits :

* ```D``` : Supprimer un commit
* ```E``` : Editer un commit
* ```R``` : Reformuler un commit
* ```S``` : _Squash_ = Regrouper des commits et les fusionner en un seul
* ```F``` : Prépare un _Fixup_ sur un commit en vue du prochain _Rebase_
* ```C``` : Copier un commit (_cherry-pick_)

### Branches

* ```N``` : Créer une nouvelle branche
* ```Ctrl + O``` : Copier le nomde la branche sur le _clipboard_
* ```O``` : Effectuer une _Pull request_
* ```R``` : Renommer une branche
* ```Espace``` : Réalise un _checkout_ = Basculer sur une nouvelle branche
* ```M``` : Merge dans la branche actuelle
* ```U``` : Ouvrir les options pour _Upstream_
* ```W``` : Ouvrir les options de _Worktree_

### Remotes :

* ```F``` : _Fetch_ _Remote_
* ```N``` : Effectuer un _Remote_
* ```E``` : Editer un _Remote_
* ```D``` : Supprimer un _Remote_

### Stash :

_Le stash correspond à enregistrer l’état actuel du répertoire de travail et de l’index, afin de revenir à un répertoire de travail propre_

* ```Espace``` : Appliquer le _Stash_
* ```R``` : Renommer le _Stash_
* ```D``` : _Drop_ = Supprimer une entrée de la liste des entrées de remisage
* ```G``` : _Pop_ = Supprimer un seul remisage de la liste des remisages et l’appliquer par dessus l’état de l’arbre de travail actuel
* ```N``` : Nouvelle branche (rappel)