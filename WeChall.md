
# EXAMEN-SYS1
WeChall
# Guide pour les niveaux de WeChall (0-5)

Bonjour

Je vais vous expliquer les étapes pour obtenir les mots de passe de WeChall niveaux 0 à 5.

1. **Inscription sur WeChall :**
   - Commencez par vous inscrire sur [WeChall](https://www.wechall.net).
   - Saisissez le mot de passe WeChall et confirmez-le en le retapant en bas.

2. **Connexion via SSH :**
   - Vous verrez l'adresse IP fournie pour vous connecter via SSH dans Putty. 
     - Exemple : `ssh -p 125643 randria@warchall.net`.
   - Ouvrez Putty et connectez-vous avec les informations fournies.
     - Exemple :
       ```
       Login: Rakoto
       rakoto@192.168.178.128's password: rakoto
       ```

3. **Résolution des niveaux :**
   - Une fois connecté, entrez l'adresse IP de WeChall, c'est-à-dire `ssh -p 125643 randria@warchall.net`.
   - Saisissez le mot de passe WeChall, et maintenant vous pouvez résoudre les niveaux de WeChall.

4. **Commandes importantes à retenir :**
   - `cd` : Change le répertoire.
   - `pwd` : Affiche le répertoire actuel.
   - `ls` : Affiche le contenu d'un répertoire.
   - `ls -al` : Affiche les fichiers cachés.
   - `cat` : Permet de lire un fichier.
   - `chmod` : Commande pour changer les autorisations de fichier.
   - `chmod +r` : Ajoute les autorisations de lecture au fichier.
   
### Niveau 0
Utilisez pwd dans le répertoire actuel
'''bash
cd /home/level
ls
cd 00_*
ls
cat Mot de Passe:"Bitwarrior"

### Niveau 1
Utilisez cd pour changer de répertoire.
cd blue ; hats ; grey ; solution ; patience
cat Mot de passe : "patience"

### Niveau 2
cd documents
ls
cat Mot de passe : "level02"

### Niveau 3
Utilisez ls –al pour voir les dossiers et fichiers cachés.
cd .bash_history
Mot de passe : "RepeatingHistory"

### Niveau 4
Revenez dans le dossier de départ.
 ls
cd level
cd 04_*
ls
chmod +r  # Pour modifier les autorisations du fichier en lecture pour l'utilisateur.
cat README2.md Mot de passe : "AndOfCourseIDoKnowChown"

### Niveau 5
cd /home/level 05_*
ls
cat README.md Mot de passe : "OKPRIVATE"


