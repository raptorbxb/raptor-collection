# Raptor Collection

### GitHub

GitHub est le service en ligne qui héberge mon repository.

Il contient une copie distante du projet


### GitHub Pages

GitHub Pages utilise le contenu de mon repository pour publier mon site internet. 


## Git et GitHub : le principe

Mon PC contient une copie locale du repository :
    💻 PC
    📁 raptor-collection
    ├── index.html
    ├── README.md
    └── .git

GitHub contient le repository distant :
    ☁️ GitHub
    📁 raptor-collection
    ├── index.html
    └── README.md

La copie locale connaît l'adresse du repository GitHub grâce à `origin`. (info sauvegardée dans le dossier .git)

GitHub ne sait pas où se trouvent mes copies locales.

## Commandes Git

### `git status`
Permet de demander à Git quelles modifications ont été effectuées dans le dossier.

### `git clone`
Permet de copier un repository GitHub sur mon ordinateur et de configurer le lien avec le repository distant.

### `git add`
Ajoute des modifications à la prochaine version à enregistrer.

### `git push`
Permet d'envoyer mes commits locaux vers GitHub.

### `git pull`
Permet de récupérer les modifications présentes sur GitHub.



## À retenir
Modifier un fichier localement ne modifie pas automatiquement GitHub, il faut push avec Git pour cela.
Le passage de mes modifications vers GitHub se fait avec Git.
