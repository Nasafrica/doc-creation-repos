# Transformation d'un dossier local en dépôt git

- `git init` : va créer un répertoire caché qui va contenir toutes les infos de l'historique de notre projet

ATTENTION : on n'est pas sensé intervenir directement dans ce dossier, il appartient à git, si on fait des modifs dedans c'est à nos risques et périls

- `git add .` : on ajoute au versionning les fichiers de notre projet. Ainsi, git va surveiller les modifications sur ces fichiers et nous alerter afin qu'on ajoute la version modifiée à l'historique  

- `git commit -m "message"` : on crée une archive du projet en l'état pour l'ajouter à l'historique. On fera attention à mettre un message de description du commit le plus parlant possible afin, en un coup d'oeil, de savoir d'où on en était quand on a créé cette archive

- création d'un dépôt vide sur github. Si on laisse les réglages par défaut, à la validation on obtient une liste des commandes à effectuer dans le terminal afin de relier notre dossier local au repo distant sur github
Par défaut, en local, le repo distant est désigné sous le nom origin

- `git remote add origin adresse_ssh_du_repo`

