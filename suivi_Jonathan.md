# Suivi J1 — Cap Web

Note ton avancée après chaque TP. Reste factuel, sans données personnelles. Ce fichier te sert pour la capsule et le bilan.

## TP00 — Diagnostic

- Hypothèse : Problème avec le CSS
- Action : La structure du HTML a été corrigé, et le CSS a été ajusté.
- Résultat : La page maintenant s'affiche correctements en double clic, les étiquettes fonctionnent, et le bouton a été corrigé
- Point non compris : Certaines logiques/comportements CSS à revoir

## TP01 — Démarrer

- Hypothèse : La page sera afficher normalement avec le HTML et le CSS mais les fonctionnalités liées à JavaScript ne fonctionneront pas
- Action : comme me l'a dis la consigne j'ai simplement vérifier l'environnement, le serveur et regarder le code HTML
- Résultat : La page est correctement affiché
- Point non compris :

## TP02 — HTML

- Hypothèse : si je remplace main par div, la structure de la page changera car il y a des paramètres CSS qui cible main
- Action : j'ai ajouté le header, j'ai ajouté section, j'ai ajouté la liste ul#messages et j'ai ajouté footer avec span#version
- Résultat : La structure HTML est maintenant comme elle devrait l'être
- Point non compris :


## TP03 — Formulaire

- Hypothèse :
- Action : Ajout des labels, rajout du textarea limité à 280 catactères, nouveau code dans app.js
- Résultat : le formulaire est présent et utilisable + les retours à la lignes peuvent être effectué avec Entrée.
- Point non compris :

## TP04 — Responsive

- Hypothèse : 
- Action :
- Résultat :
- Point non compris, test 360 / 1280 :

## Commandes essayées

Note chaque commande avec son dossier de lancement et son résultat exact. Exemple d'état local, depuis la racine étudiante :

```sh
# depuis RACINE_ETUDIANT
git status
git diff
```

Mes essais :

- Dossier : Racine
- Commande et résultat : node --version : v24.20.0
- Problème exact si blocage : 

- Dossier : Atelier
- Commande et résultat :
    npm start : Cap Web prêt sur http://127.0.0.1:3000/
- Problème exact si blocage : blocage si je retape la commande alors qu'un serveur est déjà lancé

Si Node ou Git bloque, note le message exact et continue en local sans attendre. Le double-clic sur `diagnostic/index.html` ne remplace pas le serveur pour les modules et l'envoi du TP03.

## Auto-revue finale

- Ce qui s'affiche bien : Le formulaire permet de saisir et d'envoyer un message au clavier. Le statut est mis à jour par le JavaScript fourni.
- Ce qui reste fragile au clavier ou à 360 px :
- Ce que je veux revoir en capsule : La structure html et CSS est a retravailler

## Rappel Git prudent

Git reste optionnel le matin. Vérifie l'état local, ne valide que des fichiers nommés un par un et seulement si Git est configuré. Reste en local ou en ZIP sauf si le formateur précise le circuit avec fork personnel. Aucune invitation ni demande de fusion requise le matin.

## Liens

- [README](README.md)
- [TP00](tp/00-diagnostic.md)
- [TP05](tp/05-bilan.md)
- [Aide-mémoire](ressources/aide-memoire.md)
