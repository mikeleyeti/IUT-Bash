# Système - `BASH`

## 1.1 Terminal, home, history
- Ouvrir un terminal <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd>  
- Chemin absolu du home de *john* : `home/john/`  
- `/home/` est un dossier qui contient tous les dossier personnels des utilisateurs  
- ⬆️ ou ⬇️ pour accéder à l'historique des commandes  
- ⬅️ ou ➡️ pour corriger dans la ligne

## 1.2 Arborescence, cd et ls
- `ls` : affiche le contenu du répertoire actuel
- `cd <adresse>` : se déplacer vers le dossier à l'adresse spécifiée en argument
- `cd ..` : se déplacer dans le répertoire parent
- `cd` : *sans argument* -> se déplacer dans le **home**
  
## 1.3 cat, tabulation
- `cat <fichier>` : lecture du fichier passé en argument
- La touche <kbd>Tab</kbd> permet la complétion automatique

## 1.4 Chemins absolus et relatifs
- Un **chemin relatif** fait référence à un emplacement qui est relatif à un répertoire courant. Les chemins relatifs utilisent deux symboles spéciaux, le point (`.`) et deux pointillés (`..`), qui correspondent au répertoire courant et au répertoire parent.
- Un **chemin absolu** est un chemin qui indique l'integralité du chemin de destination en partant de la racine. Un chemin absolu commence donc toujours par "slash" `/` et ce "slash" s'appelle la racine. Contrairement à un chemin relatif, un chemin absolu ne dépend pas de l'endroit où tu te trouves.

## 1.5 Commandes, arguments et options
- Une **commande** est un fichier exécutable
  - les commandes les plus indispensables sont dans le répertoire `/bin/` ,
  - les commandes accessibles à tous les utilisateurs sont dans le répertoire `/usr/bin/` ,
  - Certaines commandes ne sont accessibles qu'aux administrateurs du système (nous en reparlerons plus tard). Les commandes d'administration sont dans le répertoire `/sbin/` .
- Une option est un argument qui est spécifié par 
  - un simple `-` : version courte de l'option
  - un double `--` : version longue de l'option

## 1.6 Complément chemins
- `tree <rep>` : affiche du répertoire passé en argument
- `~` : raccourci chemin `home` personnel

## 2.1 Nano
- `nano <fichier>` : ouvre le fichier dans l'éditeur de texte `nano`, éditeur intégré à la console
- 