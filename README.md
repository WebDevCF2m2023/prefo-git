# Préfo-git

**Cours de préformation sur les commandes (de base) UNIX et DOS, et sur GIT - GITHUB**

## Arborescence

- [UNIX](#unix) (LINUX - MAC - etc...)
- [DOS](#dos) (WINDOWS)
- [GIT](#GIT)
- [Ressources GIT](#ressources-git)
- [Github](#githubcom)
- [Ressources GITHUB](#ressources-github)
- [Compte github](#compte-github)

## UNIX

- [Retour à l'arborescence](#arborescence)

Unix est un système d'exploitation créé par Bell Labs en 1969 sous la forme d'un système d'exploitation multitâche et multi-utilisateur.

Il repose sur un interpréteur ou superviseur ( le [shell](https://fr.wikipedia.org/wiki/Shell_Unix) ) et de nombreux petits utilitaires, accomplissant chacun une action spécifique, commutables entre eux (mécanisme de « redirection ») et appelés depuis la ligne de commande (PowerShell par exemple sous Windows, car Windows utilise le langage natif [DOS](#dos) si on exécute `cmd.exe`).

Ken Thompson et Dennis Ritchie sont considérés comme les inventeurs d'Unix. Par jeu de mots, le nom UNIX découle de celui d'un système antérieur, Multics.

Il est important de savoir que différents systèmes d'exploitation actuels utilisent les commandes de cette "base" commune : Linux (principal OS pour les serveurs web), IOS, macOS, Android, etc ...

[Pour en savoir plus sur UNIX - wikipédia](https://fr.wikipedia.org/wiki/Unix)

Il est important de connaitre les commandes de base pour s'en "sortir" avec GIT, et même pour de nombreux autres langages ou logiciels utilisé via [SSH](https://fr.wikipedia.org/wiki/Secure_Shell).

### Principales commandes UNIX

Liste des principales commandes que nous utiliserons :

- [pwd](https://man.openbsd.org/pwd)  affiche le chemin absolu du répertoire courant
- [ls](https://www.techonthenet.com/unix/basic/ls.php) affiche les répertoires et les fichiers du répertoire actif
    - ls (affiche seulement les noms)
    - ls toto* (affiche les fichiers commençant par toto)
    - ls -l (affiche le format long : types + droits + Nbre de liens + ....)
    ...
- [cd](https://www.techonthenet.com/unix/basic/cd.php) change de répertoire
    - cd chemin (vers le répertoire dont le chemin absolu est donné)
    - cd .. (répertoire parent)
    - cd ~ (répertoire de base)
    - cd - (répertoire précèdent)
    - cd / (répertoire racine)

- [cp](http://www.linuxcertif.com/man/1/cp/) copie
    - cp rapport.txt rapport2.txt (crée une copie d'un fichier)
    - cp * nomdossier -r (copie le contenu, fichiers et dossier dans le dossier choisi)
- [mv](https://www.techonthenet.com/unix/basic/mv.php) (move, renomme et déplace un fichier)
    - mv source destination
    - mv * dossier (déplace tous les fichiers du répertoire actif vers le répertoire dossier)
- [mkdir](https://www.techonthenet.com/unix/basic/mkdir.php) (créer un répertoire)
    - mkdir répertoire
    - [rmdir](https://man.openbsd.org/rmdir) (effacer un répertoire)
    - rmdir dossier (supprime un répertoire vide)
- [rm](https://man.openbsd.org/rm) (remove, efface!!!)
    - rm fichier
    - rm -i fichier (interactivement, avec demande de confirmation)
    - rm -f fichier (avec force, sans demande de confirmation)
    - rm -r fichier (avec récursivité, avec les sous répertoires)
    - rm -rf dossier (supprime le répertoire et tout son contenu, sans confirmation)
- [echo](https://www.wikiwand.com/fr/Echo_(Unix)) affiche du texte et peut remplir un fichier
    - echo "blabla"
    - echo "Avec une redirection vers un fichier" > test.txt

Pour les autres commandes principales (grep, vi, etc...), la documentation est vaste sur internet !

Voici un Cheat sheet en cas de besoin :
- [Cheat sheet Unix en pdf](https://github.com/WebDevCF2m2022/prefo-git/blob/main/files/Unix_command_cheatsheet.pdf)

## DOS

- [Retour à l'arborescence](#arborescence)

On appelle généralement DOS (disk operating system) le système d'exploitation PC-DOS, ainsi que la variante MS-DOS vendue par Microsoft pour les compatibles PC.

Comme nous travaillons actuellement sous Windows, il est intéressant de connaitre quelques commandes de base :

- md (Make Directory, pour créer un répertoire)
- cd (Change Directory, pour changer de répertoire de travail)
- rd (Remove Directory, pour détruire un répertoire)
- copy (pour copier des fichiers)
- dir (pour lister les fichiers)
- cls (abréviation de CLear Screen pour effacer l'écran)
- del (pour détruire un fichier)

Pour une liste plus complète :

https://fr.wikibooks.org/wiki/COMMAND.COM

## GIT

- [Retour à l'arborescence](#arborescence)

Git est un logiciel de gestion de versions décentralisé gratuit et open source conçu pour gérer tout,
des petits aux très grands projets avec rapidité et efficacité.

C'est un logiciel libre créé par Linus Torvalds, auteur du noyau Linux, et distribué selon les termes de la licence publique générale GNU version 2.

Depuis 2010, il est de loin le système de versions le plus utilisé dans le monde du web comme dans le développement en général, aussi bien pour les projets open source que commerciaux.

Lorsqu'on lui demande l'origine de ce nom "git",
qui est à peu près l'équivalent de "connard" en argot britannique, Linus Torvalds a répondu :

> “je ne suis qu'un sale égocentrique, donc j'appelle tous mes projets d'après ma propre personne. D'abord Linux, puis Git.”

## Ressources GIT

- [Retour à l'arborescence](#arborescence)

Vous pouvez télécharger GIT sur le site officiel :

https://git-scm.com/

Vous y trouverez également de la documentation relativement complète online.

Je vous ai mis la dernière version de progit.pdf dans le dépôt (repository) actuel :

- [progit](https://github.com/WebDevCF2m2022/prefo-git/blob/main/files/progit.pdf)

Git Cheat Sheet en PNG:
![git-cheat-sheet.png](https://github.com/WebDevCF2m2022/prefo-git/blob/main/files/git-cheat-sheet.png "git-cheat-sheet.png")

Un memento Linux :
- [memento_linux.pdf](https://github.com/WebDevCF2m2022/prefo-git/blob/main/files/memento_linux.pdf "memento_linux.pdf")

## GitHub.com

- [Retour à l'arborescence](#arborescence)

Si ce nom est encore inconnu pour beaucoup d’internautes, il désigne pourtant l’un des sites les plus visités au monde. En une décennie d’existence, il est devenu un outil incontournable pour les développeurs informatiques, qu’ils soient indépendants ou employés des grandes entreprises de la Silicon Valley.

GitHub permet aux développeurs de stocker et de partager, publiquement ou non, le code qu’ils créent. La plate-forme accueille ainsi, dit-elle, plus de 80 millions de projets, qu’il s’agisse de logiciels, de sites Web, d’applications pour mobile ou tous autres types de programme informatique — et ce quel que soit le langage de programmation utilisé.

Microsoft a acheté, lundi 4 juin 2018. La firme américaine a annoncé avoir acquis pour 7,5 milliards de dollars (6,4 milliards d’euros) la plate-forme de développement de logiciels GitHub.

Cela inquiète de nombreux développeurs. Parmi ses concurrents, le site de forge, GitLab voit 50 000 nouveaux projets apparaître sur sa plateforme dans la journée via l'outil de migration depuis GitHub. 

Le mercredi 6 juin, 100 000 projets avaient migré sur les 75 millions de projets que comporte GitHub. D'autres se sont tournés vers Bitbucket. SourceForge.net, une des plus anciennes forges publiques voit aussi un important pic d'imports et comme les précédents proposent un outil spécialisé pour l'import depuis GitHub. Enfin, d'autres se sont probablement portés vers des solutions d'auto-hébergement libres de leurs dépôts.

En 2019, est mis en place une restriction d'échanges des États-Unis d'Amérique, dont l'Iran, la Syrie, la Crimée, et potentiellement d'autres pays (Github mentionne Cuba et la Corée du Nord). 

Certains comptes de développeurs russes auraient été bloqués depuis le début de la Guerre en Ukraine. En réponse, le 29 juillet 2019, le ministère des Affaires étrangères russe a annoncé que le gouvernement russe allait migrer vers une plateforme de développement nationale, GitLab.

Le milieu de l'open Source s'opposant à une politique trop stricte, GitHub a annoncé que " ... Nous continuons à veiller à ce que les services open source gratuits soient accessibles à tous, y compris aux développeurs en Russie ... ". 

Le 25 Janvier 2023, GitHub publie un article pour annoncer avoir dépassé la barre des 100 millions d'utilisateurs.


Nous utiliserons github.com pour stocker nos fichiers et travailler sur les projets tout le long de la formation.

Si vous n'avez pas encore de compte, créez-en un avec une adresse mail valide.

Notre groupe se trouvera à cette URL pour cette session de formation:

https://github.com/WebDevCF2m2023

## Compte Github

- [Retour à l'arborescence](#arborescence)

Si vous avez déjà un compte github, vous pouvez passer la première étape de l'inscription.

### Inscription

Rendez-vous à l'adresse ci-dessous et utilisez un mail auquel vous avez accès (et que vous garderez !).

https://github.com/signup

N'oubliez pas votre mot de passe, même si vous pourrez le mettre à jour via votre mail.

Choisissez un username qui pourra être montré à un employeur !

### Connexion github

Connectez-vous à votre compte sur https://github.com/ puis envoyez-moi votre username sur teams que je puisse vous rajouter au projet :

https://github.com/WebDevCF2m2023

### Lier votre compte et votre PC

Dans la console Git ou Powershell, tapez cette ligne avec le mail utilisé pour se connecter à github :

    ssh-keygen -t ed25519 -C "votremail@utilisepourgithub.com"

Ne mettez pas de passphrases, inutiles dans le cadre d'une formation, puis ajoutez la clef avec le code ci-dessous

    ssh-add ~/.ssh/id_ed25519
    eval "$(ssh-agent -s)"
    ssh-add ~/.ssh/id_ed25519

Ensuite copiez la clef publique avec cette commande :

    clip < ~/.ssh/id_ed25519.pub

Cliquez sur ce lien puis pour créer un clef SSH sur github :

https://github.com/settings/ssh/new

Et rajoutez la clef publique que vous trouverez dans le champ key en collant le résultat de la commande précédente.

Dans cette même console, liez votre ordinateur avec github:

    git config --global user.name "votre username"
    git config --global user.email votremail@utilisepourgithub.com

**Si tout va bien, nous allons pouvoir commencer à travailler ensemble !**

## Ressources GITHUB

- [Retour à l'arborescence](#arborescence)

Un aide-mémoire sur les commandes git liées à github :
- [Aide mémoire github](https://github.com/WebDevCF2m2022/prefo-git/blob/main/files/github-git-cheat-sheet.pdf)

Deux cours en ligne sont particulièrement intéressants (et il y en a de nombreux !) :
- https://openclassrooms.com/fr/courses/7162856-gerez-du-code-avec-git-et-github
- https://grafikart.fr/tutoriels/init-config-add-log-585#autoplay
