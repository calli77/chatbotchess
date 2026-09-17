# Suivi — après-midi J1

**Noté. Un fichier par étudiant, écrit avec vos mots.** Une phrase honnête (« j'ai essayé X, j'ai vu Y, je ne comprends pas pourquoi ») rapporte plus qu'une phrase parfaite recopiée.

- Nom : Jonathan Kibundu-mwela
- Binôme : Calliclès Bazolo
- Atelier utilisé (le mien, celui du binôme, la reprise) : celui du binôme

## Pour chaque TP abordé

Recopiez ce bloc autant de fois que nécessaire.

### TP07

- J'ai prédit : J'ai pensé qu'il fallait créer une 2 conditions, une quand rien n'est marqué et une autre quand quelque chose est marqué dans le formulaire.
- Nous avons fait : Nous avons récupérer le champs avec trim, puis nous avons ajouté le message dans un nouvel élément li.
- J'ai observé : Un message est maintenant ajouté à la conversation
- J'ai compris : textContent permet d'afficher une chaîne de caractères comme du texte
- Je n'ai pas compris :
- Réponse à la question « Dans le suivi » du TP : innerhtml crée une balise le mot gras aurait été affiché en gras, alors que textcontent affiche du texte brut 

### TP08

- J'ai prédit : Qu'il fallait rajouter des règles en Javascript pour que le bot puissent reconnaîtres certains messages et répondent de manière appropriés.
- Nous avons fait : Nous avons crée brain.js avec les fonctions demandés et nous l'avons importés comme demandé
- J'ai observé : Le chatbot reconnaît les messages que j'ai envoyé 
- J'ai compris : je me suis rappelé que mettre un triple égale "===" permet d'ignorer les majuscules/minuscules de plus j'ai compris que brain.js contient la logique du bot
- Je n'ai pas compris :
- Réponse à la question « Dans le suivi » du TP : brain.js ne gère pas l'affichage de la page seulement la logique du bot.

### TP09

- J'ai prédit : Qu'on devait séparer la logique des fichiers js avec pour que chaque fichier ait leur propre domaine afin d'avoir une architecture plus logique et scalable
- Nous avons fait : crée view.js pour gérer l'architecture de la page, dans app.js historique a été crée pour l'historique de toute la conversation.
- J'ai observé : Rien a changé on a juste rendu l'architecture meilleure
- J'ai compris : Je l'avais déjà compris mais séparé les fichiers est quelque chose de nécessaire dans un projet pour éviter le code spaghetti et mieux s'y retrouver
- Je n'ai pas compris : Je dois quand même apprendre a mieux savoir de quel manière séparé les fichiers, quand il faut le faire et quand il faut pas le faire
- Réponse à la question « Dans le suivi » du TP : brain.js gère comment le chatbot répond selon le message envoyé, view.js sert a l'affichage et app.js coordonne toute la logique js

### TP10

- J'ai prédit : Faire une sauvegarde local pour garder l'historique de la conversation a chaque fois qu'on retourne sur le chat, de plus avoir une option pour effacer cette historique et repartir de zéro
- Nous avons fait : Il fallait utiliser localstorage pour enregistrer l'historique de la conversation et la mettre à jour après chaque message. Nous avons utilisé un try/catch pour éviter qu'une mauvaise donnée puisse passer. De plus on a rajouté un bouton pour effacer la conversation
- J'ai observé : Le bouton marche et la conversation est sauvegardé
- J'ai compris : Je le savais déjà mais localStorage permet de conserver les données en local même lorsque la page est rechargés
- Je n'ai pas compris :
- Réponse à la question « Dans le suivi » du TP :

### TP…

- J'ai prédit :
- Nous avons fait :
- J'ai observé :
- J'ai compris :
- Je n'ai pas compris :
- Réponse à la question « Dans le suivi » du TP :

## Épreuve de l'explication (TP12)

- Ce que je n'ai pas su expliquer :
- Ce que mon binôme n'a pas su expliquer :

## Trois questions

1. Pourquoi `textContent` et pas `innerHTML` ?

textContent affiche du text brut alors que innerHTML est considéré comme une balise html

2. Pourquoi trois fichiers plutôt qu'un seul ?

Pour séparer les responsabilités, view.js pour l'affichage, brain.js pour les règles du chatbot, et app.js pour tout coordonner

3. Si demain une IA écrit une partie du code, comment saurai-je qu'il est correct ?

Je ne peux pas simplement tout confier à l'IA je dois vérifier ce qu'il fait, le tester et le comprendre.

## Aides utilisées

- Indices, aide-mémoire, voisins :
- Ce que j'ai demandé à une IA, et comment j'ai vérifié sa réponse :
