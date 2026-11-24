# TP : Les formulaires JavaScript (TI13)

Matière : Développement web côté client (JavaScript et DOM)
Établissement : ISET Nabeul
Classe : TI13
Durée indicative : 3 heures

> Document de référence : le sujet du TP est écrit par l'enseignante. Ce résumé le décrit avec ses propres mots et ne reprend pas le sujet. Les droits sur le sujet doivent être confirmés avant publication.

## Objectif

Lire un formulaire HTML, le contrôler et afficher des résultats avec JavaScript, en manipulant le DOM.

## Exercice 1 : calcul de la moyenne

- Saisir deux notes, nombres réels compris entre 0 et 20.
- Calculer la moyenne : (note 1 + note 2) / 2.
- Afficher « Monsieur » ou « Mademoiselle » selon le genre sélectionné.
- Afficher le nom en majuscules et le prénom en minuscules.
- Afficher la moyenne, puis « résultat = échec » si elle est inférieure à 10, sinon « résultat = succès ».
- La fonction s'exécute au clic sur le bouton Envoyer.

## Exercice 2 : calcul de l'IMC

- IMC = poids / (taille × taille).
- Le poids et la taille doivent être des nombres réels strictement positifs.
- Afficher le résultat dans une boîte de dialogue.

## Exercice 3 : formulaire d'achat

- Au chargement de la page, afficher la date du jour au format jj/mm/aaaa.
- Afficher dans le champ prix le prix de l'article choisi dans la liste (cinq articles, un tableau de prix).
- Contrôler le champ d'avance quand il perd le focus : la valeur doit être numérique, sinon un message s'affiche et le champ est vidé.
- Calculer le total à payer au clic sur Valider votre choix. Le sujet prévoit des frais de livraison de 150 dt hors du grand Tunis, et aucun frais si le client retire l'article en magasin. La règle exacte pour le grand Tunis n'est pas lisible dans le document consulté : à vérifier avec le sujet original.

## Points à retenir

- Les contrôles de saisie (nombre, intervalle, valeur positive) reviennent dans chaque exercice.
- Les fonctions sont appelées depuis les événements du formulaire : clic, chargement de la page, perte de focus.
