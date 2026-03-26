# TP1-HaniaELGUIZI0030-22
## 🎯 Objectif
J’ai compilé et exécuté le programme Java à l’aide des commandes `javac Main.java` et `java Main`.  
Le programme affiche le message "Bonjour Git" dans la console.
![capture](https://github.com/user-attachments/assets/e12943a1-6ed8-4da6-9fa2-9d0614eed68e)

J’ai exécuté la commande `git status` pour vérifier l’état du dossier.  
Git indique que ce dossier n’est pas encore un dépôt Git et qu’aucun fichier n’est suivi.
<img width="467" height="215" alt="image" src="https://github.com/user-attachments/assets/f909e4df-8449-42eb-9e6e-9184124a7026" />

J’ai utilisé la commande `git init` pour initialiser le dépôt Git.  
Cette commande crée un dossier caché `.git` et transforme le dossier en dépôt Git.
Après l’initialisation, j’ai exécuté `git status`.  
Git détecte les fichiers `Main.java` et `Main.class` comme fichiers non suivis (untracked).
J’ai utilisé la commande `git add Main.java` pour ajouter le fichier au suivi Git.  
Le fichier devient alors prêt à être enregistré dans un commit.
<img width="488" height="224" alt="image" src="https://github.com/user-attachments/assets/1130a416-9d6f-4fc2-a486-a1384aa89845" />

Après avoir ajouté le fichier, la commande `git status` montre que `Main.java` est prêt à être commit (staged).
J’ai créé un fichier `.gitignore` pour ignorer les fichiers compilés Java (`.class`).  
Cela permet d’éviter d’ajouter des fichiers inutiles dans le dépôt.
Après le commit, la commande `git status` indique qu’il n’y a rien à enregistrer.  

<img width="605" height="209" alt="image" src="https://github.com/user-attachments/assets/0496268b-8b0f-40d4-bad5-8b5668186357" />

J’ai configuré mon nom et mon email avec `git config` afin d’associer mes commits à mon profil.
J’ai effectué le premier commit avec la commande `git commit -m "Premier commit Java"`.  
Ce commit enregistre le fichier `Main.java` et le fichier `.gitignore`.

<img width="599" height="182" alt="image" src="https://github.com/user-attachments/assets/4b780460-3854-42c2-ab7e-16bdd2cfd490" />

J’ai utilisé la commande `git log` pour afficher l’historique des commits.  
Le premier commit apparaît avec son message et ses informations.
J’ai utilisé la commande `git add -A` pour ajouter tous les fichiers non suivis dans le dépôt.
La commande `git status` montre que les fichiers `notes.txt` et `Main.class` sont prêts à être commit.
<img width="596" height="233" alt="image" src="https://github.com/user-attachments/assets/d2843e22-2a2b-4b4a-b92d-ce47933f5edb" />

La commande `git log` montre les deux commits effectués :  
- Premier commit Java  
- Ajout du fichier notes
<img width="562" height="291" alt="image" src="https://github.com/user-attachments/assets/666094b6-1418-4c1d-9930-d074b7ec4851" />
