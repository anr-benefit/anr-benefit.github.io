# ANR BENEFIT

## Présentation

Le site web se base sur le système de publication [Quarto](https://quarto.org/).
L'arborescence de ce dépôt GitHub est la suivante:

```
root/
├─ index.qmd
├─ roadmap.qmd
├─ about.qmd
├─ bibliography.bib
├─ _quarto.yml
├─ scientific_production.qmd
├─ softwares.qmd
├─ technical_reports/
│  ├─ bibliography.bib
│  ├─ tech_report_1.qmd
├─ imgs/
│  ├─ anr_logo.png
```

- `_quarto.yml` : Fichier YAML permettant de définir les grandes lignes du site (titre, barre de navigation, etc).
- `index.qmd` : Il s'agit de la page d'accueil du site.
- `about.qmd` : Il s'agit de la page présentant rapidement les différents partenaires du projet.
- `roadmap.qmd` : Il s'agit de la page résumant le planning soumis pour le déroulement du projet.
- `scientific_production.qmd` : Cette page, pour le moment inutilisée, permettra à terme de lister toute la production scientifique issue du projet.
- `softwares.qmd` : Page présentant certains des logiciels/bibliothèques développées et utilisées par les membres du projet ANR.
- `technical_reports` : Dossier contenant les différents rapports techniques. Le document `tech_report_1.qmd` contient un exemple issu d'un autre projet ANR et n'est pas listé sur le site en ligne.

## Comment modifier le site ?

Le système de publication [Quarto](https://quarto.org/) se base sur une variante de `markdown` très simple à prendre en main.
Une fois que vous avez installer `Quarto` sur votre machine, il est très simple d'apporter des modifications à des pages déjà existantes:

1. Modifier le ou les fichiers `.qmd` souhaités.
2. Faites un `git commit`/`git push` pour enregistrer vos modifications.
3. Dans un terminal, tapez la commande `quarto publish gh-pages` pour déployer le site en ligne via Github Pages.

Et voilà.
Pour rajouter des pages, n'hésitez pas à me contacter ([jean-christophe.loiseau@ensam.eu](mailto:jean-christophe.loiseau@ensam.eu)) ou à regarder la documentation en ligne de [Quarto](https://quarto.org), elle est plutôt bien faite.
