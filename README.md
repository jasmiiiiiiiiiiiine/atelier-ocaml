# Atelier OCaml

Site de révision pour les TD Caml 1 et 2 (Info-sup S1, EPITA) : récursion, listes et ordre supérieur.

## Contenu

- **Cours** : syntaxe, opérateurs, motifs, squelette récursif, pièges fréquents, récap des fonctions et méthode.
- **Corrections** : les fonctions des TD (`identic`, `shared`, `rev`, `assoc`, `flatten`, `gcd`, `loop`, `find_power`, `map`, `for_all`, `exists`, `is_sorted`, `find`, `filter`, `partition`, `unzip`, `count`), chacune avec un mode « Essayer » qui l'exécute pas à pas.
- **Exercices en trois niveaux**, tirés au hasard :
  - *Niveau 1 · Type TD* : prédire le résultat d'une fonction du TD, trouver l'erreur, compléter le code, écrire une fonction simple.
  - *Niveau 2 · Intermédiaire* : appels combinés (`map f (filter p l)`…), questions « quel est le type ? », fonctions plus dures (`merge`, `split_at`, `zip`…).
  - *Niveau 3 · Type partiel* : problèmes en plusieurs questions avec barème (ensembles, polynômes, suite de Conway, `fold`, tables d'association), types difficiles.
- **Examen blanc** : sujet complet chronométré (1 h, 1 h 30, 2 h ou sans limite), noté sur 20 — questions courtes notées par le site (6 pts), deux fonctions (6 pts) et un problème (8 pts). Historique des notes.

Les résultats attendus des exercices générés sont calculés par le site ; toutes les solutions, signatures et types ont été vérifiés avec OCaml 4.14. La correction du code par Claude ne fonctionne que dans la version publiée sur claude.ai ; ailleurs, on compare avec la solution et on se note soi-même.

Le site tient dans un seul fichier, `index.html`, sans dépendance à installer.

## Fiche de cours

`fiche/fiche_ocaml.pdf` et sa source LaTeX `fiche/fiche_ocaml.tex` (à compiler avec XeLaTeX, deux fois).

## Mettre le site en ligne avec GitHub Pages

Settings → Pages → Source : *Deploy from a branch* → branche `main`, dossier `/ (root)`.
