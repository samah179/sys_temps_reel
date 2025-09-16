# CR Lab2 – Git

## Commandes utilisées

1. Installation des packages :
sudo apt install git gitk git-email

2. Configuration de Git :
git config --global user.name "samah"
git config --global user.email arabsamah1@gmail.com
git config --global user.name
git config --global user.email

3. Création d’un répertoire test :
mkdir test
cd test

4. Création d’un fichier :
echo "hello M2 syscom" > samah

5. Initialiser un dépôt :
git init

6. Vérifier l’état :
git status

7. Ajouter le fichier :
git add samah
git status

8. Premier commit :
git commit -m "Premier commit"

9. Création d’un repo vide sur GitHub (via interface web)

10. Connecter et pousser :
git remote add origin https://github.com/samah179/sys_temps_reel.git
git push -u origin master

11. Mémoriser identifiants :
git config credential.helper store

12. Création d’un README.md (via interface GitHub)

13. Mise à jour locale :
git pull origin master

14. Clonage du repo :
cd ~/Downloads
git clone https://github.com/samah179/sys_temps_reel.git
