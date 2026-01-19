20 COMMANDES A SAVOIR

Installer Git sur pc, puis créer un compte sur github
https://git-scm.com/install/
https://github.com

1. Démarrer et configurer
● git config --global user.name "Ton Nom" : configurer le nom utilisé dans
les commits.
● git config --global user.email "ton@email.com" : configure l’email
associé aux commits.
● git init : initialise un nouveau dépôt Git dans un dossier.
● git clone <url> : copie un dépôt existant (ex : depuis GitHub) sur ta machine.

2. Suivre les fichiers et enregistrer
● git status : montre les fichiers modifiés, suivis/non suivis et la branche actuelle.
● git add <fichier> / git add . : ajoute un fichier (ou tous) à la zone de
staging.
● git commit -m "message" : enregistre un snapshot des fichiers ajoutés avec un
message.1
● git log : affiche l’historique des commits de la branche.
● git diff : montre les différences entre l’état actuel et l’index ou un
commit.leptidigital+1

3. Travailler avec GitHub (distant)
● git remote add origin <url> : lie ton dépôt local à un dépôt distant (souvent
GitHub).
● git push -u origin main : envoie la branche locale main vers le dépôt distant
pour la première fois.olivier.
● git push : pousse les nouveaux commits locaux vers le dépôt distant.
git pull : récupère et fusionne les changements du dépôt distant dans ta branche
locale.
● git fetch : récupère les nouvelles références du dépôt distant sans les fusionner.

4. Branches et versions
● git branch : liste, crée ou supprime des branches (git branch feature-x).
● git checkout feature-x ou git switch feature-x : change de branche
pour travailler sur une autre version.
● git merge feature-x : fusionne la branche feature-x dans la branche
courante.
● git tag v1.0 : crée une étiquette pour marquer une version importante (release).

5. Annuler, corriger, nettoyer
● git reset --hard <hash> : réinitialise la branche et le répertoire de travail à un
commit donné (attention, destructif).
● git revert <hash> : crée un nouveau commit qui annule les changements d’un
commit sans réécrire l’historique.
● git stash : met de côté temporairement les modifications non commit pour revenir
à un état propre.

1. https://www.datacamp.com/fr/blog/git-commands
2. https://www.hostinger.com/fr/tutoriels/commandes-git
3. https://www.leptidigital.fr/internet/commandes-git-37766/
4. https://www.sfeir.dev/product/draft-les-commande-git/
5. https://www.atlassian.com/fr/git/glossary
6. https://scalastic.io/complete-git-guide/
7. https://olivier.dossmann.net/wiki/developpement/commandes-git/
8. https://www.datacamp.com/blog/git-commands
9. https://codeur-pro.fr/comprendre-le-workflow-de-base-dun-depot-git/
10. https://www.claudebueno.com/technologies/top-20-commandes-git.htm


EXERCICE PRATIQUE GITHUB

● Tu es seul sur un petit projet (ex : mini site ou script Python).
● Tu vas : configurer Git, créer un dépôt local, versionner ton code, créer des
branches, gérer des versions, puis connecter le tout à GitHub.datacamp+1
Étape 1 – Préparer ton environnement
Objectif : installer et configurer Git pour la première fois.

1. Vérifie Git : git --version.
2. Configure ton identité :
○ git config --global user.name "Ton Nom"
○ git config --global user.email "ton@email"
3. Crée un dossier de projet : mon-projet-git et mets un premier fichier (ex :

README.md ou script.py).
Commandes clé : git --version, git config.
Étape 2 – Créer le dépôt et premier commit
Objectif : suivre ton code dès le début.

1. Place-toi dans le dossier : cd mon-projet-git.
2. Initialise Git : git init.
3. Vérifie l’état : git status.
4. Ajoute tous les fichiers : git add.
5. Crée ton premier commit : git commit -m "Initial commit".
6. Regarde l’historique : git log.
Commandes clé : git init, git status, git add, git commit, git log

#Projet pour apprendre l'utilisation de Git, Devoir pour le cours Langage de Balisage (efp)

Ceci est un test sur une branche séparée.