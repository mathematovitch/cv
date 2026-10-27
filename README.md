# CV de l'auteur de Mathématovitch (`/cv/`)

Page CV de M. Outerovitch, professeur de mathématiques, auteur du site de
cours https://mathematovitch.github.io/. Site de projet GitHub Pages (dépôt
`mathematovitch/cv`), servi à https://mathematovitch.github.io/cv/ ; extrait
avec son historique du dépôt `mathematovitch/mathematovitch.github.io`
(2026-10-28).

- `index.html` écrit à la main (aucun build), `avatar.svg` (pixel 5×5).
- Thème [Minimal](https://github.com/mathematovitch/minimal) (fork
  d'[orderedlist/minimal](https://github.com/orderedlist/minimal)) :
  `stylesheets/styles.css` sous **CC BY-SA 3.0**, avec des ajouts en fin de
  fichier (sections `<details>` dépliables). Le reste est sous
  [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.fr).
- `<meta name="robots" content="noindex">` : la page n'est pas indexée.
- Dépend du site principal par chemins relatifs : `../assets/favicon.svg`,
  `../index.html` (lien vers les cours), `../credits/index.html`.

## Aperçu local

Comme pour le terminal : lien symbolique dans le site principal (ignoré par
git là-bas), puis serveur à sa racine.

```
ln -s ~/code/04-web/cv ~/work/00.site/cv
cd ~/work/00.site && python3 -m http.server   # puis http://localhost:8000/cv/
```

## Déploiement

Push sur `main` de `mathematovitch/cv` : GitHub Pages sert le dépôt tel quel.

## 🛣️ Roadmap

- [ ] **1. Actualiser le CV** d'après le dossier I-Prof (postes, dates,
  formations continues suivies, missions) ; vérifier le niveau d'anglais
  (B2 BULATS, attestation non retrouvée). Source actuelle : CV de
  l'inspection 2026 et rapport DNL.
- [ ] **2. Étoffer le CV en général**, en repartant de la version envoyée à
  l'AEFE en 2024.
- [ ] **3. Version PDF du CV**, générée depuis la page (impression propre) ou
  depuis un `.tex`.

<details>
<summary>Déjà fait</summary>

- [x] Page CV `/cv/` (thème Minimal forké sous `mathematovitch/minimal`, avatar pixel, sections dépliables, `noindex`)

</details>
