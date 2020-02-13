# Adhérer à un énoncé sur Github Classroom

## Prérequis

### Un compte sous Github

Se créer un compte sur [GitHub](https://github.com/) et si votre identifiant n'est pas représentatif de votre nom complet, il serait une bonne idée d'ajouter votre nom complet dans la section "informations complémentaires" de votre profil.

### Git

Pour l'installation et la configuration de Git pour Windows, suivre le [tutoriel](https://astuces-informatique.com/comment-installer-utiliser-git-sous-windows/). (Faire la section "Installation de Git sous Windows" et "Configuration et connexion à un référentiel distant" étapes 1 à 3).

## Adhérer à une classe sous GitHub Classroom

### Initialisation du projet

1. Naviguer au lien d'invitation préalablement envoyé par l'enseignant
2. S'authentifier
3. Créer l'équipe en y donnant un nom d'équipe sous ce format : "NomDuCours_AlexisGaronMichaud_TitreDuDevoir" -> "ProgObjet_AlexisGaronMichaud_TP2" (sans accent et sans espaces)
4. Récupérer le lien du projet suite à la création et l'initialisation de l'équipe

### Ajouts des fichiers de bases dans le référentiel

1. Naviguez sur le projet préalablement créé
2. Initialisez les fichiers de bases du référentiel
   1. Cliquez sur "README" et ensuite sur "commit new file"
   2. Cliquez sur "Create new file", nommez celui-ci ".gitignore" et insérez le contenu du [lien](https://github.com/github/gitignore/blob/master/VisualStudio.gitignore) et cliquez sur "commit new file"

### Cloner un référentiel localement

1. Cliquez sur le bouton vert "Clone or download" et copier le lien dans la fenêtre.
2. Ouvrir une invite de commandes PowerShell
3. Naviguez jusqu'au répertoire où que l'on veuille cloner le référentiel (voir [l'astuce](https://www.addictivetips.com/windows-tips/open-powershell-in-a-specific-location/))
4. Entrez la commande "git clone UrlDuReferentiel"

### Ajouter un projet .Net existant à un référentiel fraîchement cloné

1. Copiez le projet .Net à la racine du répertoire fraîchement cloné
2. Ouvrir une invite de commandes PowerShell
3. Naviguez jusqu'au répertoire cloné
4. Exécutez les commandes suivantes :

```sh
git status                      (pour vérifier si les fichiers sont présents)
git add .                       (pour ajouter tous les fichiers)
git commit -m "commit initial"  (pour ajouter un commentaire à notre commit)
git push origin master          (pour pousser les modifications sur GitHub)
```

Pour terminer, vérifiez que le tout se retrouve sur GitHub.
