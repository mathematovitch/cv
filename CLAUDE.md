# CLAUDE.md

Page CV `/cv/` de mathematovitch.github.io (2026-10-27) : site de projet
GitHub Pages (dépôt `mathematovitch/cv`, branche `main`, aucun build),
extrait avec son historique du site principal `~/work/00.site`
(2026-10-28). Voir `README.md`.

- `index.html` écrit **à la main**, thème
  [Minimal](https://github.com/mathematovitch/minimal) (fork
  d'orderedlist/minimal) : `stylesheets/styles.css` copié tel quel
  (**CC BY-SA 3.0**, pas CC0 ; crédité dans `CREDITS` de
  `~/work/00.site/tools/build.py` et en pied de page) + ajouts en fin de
  fichier (sections `<details>` dépliables).
- Colonne de gauche volontairement sobre (avatar, nom, poste, un lien vers
  les cours, sommaire en liste `ul.sommaire`). Mail seulement en pied de
  page, non cliquable (`[at]`/`[dot]`) ; `<meta name="robots"
  content="noindex">`.
- **Données perso : mail seulement** (ni téléphone, ni adresse, ni date de
  naissance) ; **pas de mention de la certification DNL** (choix de
  l'utilisateur).
- Sources : `~/work/08.Autre/Inspection-2026/CV-Colin-Outerovitch.tex`
  (dates de référence) et le rapport DNL (`~/work/08.Autre/DNL/`).
- Avatar `avatar.svg` : grille pixel 5×5 symétrique aux couleurs du logo du
  site, fond transparent (variantes dans `~/work/00.site/dev/avatars/`).
- Liens hors dossier **relatifs** (`../assets/favicon.svg`, `../index.html`,
  `../credits/index.html`) : la page est servie à `/cv/`, sous le site
  principal. Le site principal pointe vers elle (`CV_DIR` de son `build.py`,
  auteur de l'accueil).
- Aperçu local : lien symbolique `~/work/00.site/cv → ~/code/04-web/cv`
  (ignoré par git dans le site), `python3 -m http.server` à la racine de
  `00.site`, http://localhost:8000/cv/.
- Ne jamais committer sans demande explicite de l'utilisateur.
