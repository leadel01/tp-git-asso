TP Git Association

Site web statique (HTML/CSS) pour une association, réalisé dans le cadre d'un travail pratique sur Git. Il sert à mettre en pratique la gestion de versions avec Git et GitHub : branches, commits, Pull Requests.

Prérequis
Un navigateur web récent (Chrome, Firefox, Edge, Safari)
Git pour récupérer le projet et suivre ses modifications
Un éditeur de code, par exemple Visual Studio Code

Aucune dépendance (Node.js, base de données, etc.) n'est nécessaire.

Installation
Cloner le dépôt :
bash
   git clone https://github.com/leadel01/tp-git-asso.git
Se placer dans le dossier du projet :
bash
   cd tp-git-asso
Ouvrir le dossier dans Visual Studio Code (ou un autre éditeur) :
bash
   code .
Lancement

Ouvrir le fichier index.html dans un navigateur (double-clic, ou clic droit > Ouvrir avec).

Le site s'affiche directement : il n'y a pas de serveur à démarrer.

Structure du projet
text
tp-git-asso/
├── index.html   # structure et contenu de la page
├── style.css    # mise en forme et apparence
├── .gitignore   # fichiers ignorés par Git
└── README.md    # ce fichier
Contribution
Se placer sur la branche principale et récupérer les dernières modifications :
bash
   git switch main
   git pull
Créer une branche pour sa fonctionnalité ou sa correction (une branche = une fonctionnalité ou un correctif) :
bash
   git switch -c feature/nom-de-la-fonctionnalite
Modifier les fichiers nécessaires, puis les ajouter et créer un commit :
bash
   git add .
   git commit -m "feat: description de la modification"

Les messages de commit suivent la convention Conventional Commits (feat:, fix:, docs:, style:…).

Envoyer la branche sur GitHub :
bash
   git push -u origin feature/nom-de-la-fonctionnalite
Ouvrir une Pull Request sur GitHub. Les modifications sont relues avant d'être intégrées à la branche principale.
Équipe

Projet réalisé dans le cadre du TP Git.

Membre	Rôle
Chloé LE DU	style (ex. HTML, CSS, relecture, documentation)
Prénom Nom	Rôle

À compléter avec les membres de l'équipe et leurs rôles.