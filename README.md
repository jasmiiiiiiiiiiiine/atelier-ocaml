# Atelier OCaml

Site de révision pour les TD Caml 1 et 2 (Info-sup S1, EPITA) : récursion, listes et ordre supérieur.

## Contenu

- **Cours** : syntaxe, opérateurs, motifs, squelette récursif, pièges fréquents, récap des fonctions et méthode.
- **Corrections** : les fonctions des TD (`identic`, `shared`, `rev`, `assoc`, `flatten`, `gcd`, `loop`, `find_power`, `map`, `for_all`, `exists`, `is_sorted`, `find`, `filter`, `partition`, `unzip`, `count`), chacune avec un mode « Essayer » qui l'exécute pas à pas.
- **Exercices générés au hasard** :
  - *Prédis le résultat* : appels aléatoires, réponse vérifiée par le site, déroulé affiché en cas d'erreur.
  - *Trouve l'erreur* : codes faux à diagnostiquer.
  - *Complète le code* : un trou à remplir.
  - *Écris la fonction* : énoncé, indices et solution. La correction par Claude ne fonctionne que dans la version publiée sur claude.ai ; ailleurs, on compare avec la solution.

Le site tient dans un seul fichier, `index.html`, sans dépendance à installer.

## Fiche de cours

`fiche/fiche_ocaml.pdf` et sa source LaTeX `fiche/fiche_ocaml.tex` (à compiler avec XeLaTeX, deux fois).

## Mettre le site en ligne avec GitHub Pages

Settings → Pages → Source : *Deploy from a branch* → branche `main`, dossier `/ (root)`.
