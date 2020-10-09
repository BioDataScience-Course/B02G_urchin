# Croissance de *Parocentrotus lividus* Lamarck (1816)

## Avant-propos

Cette séance d’exercices est en cours de développement. N’hésitez pas à vérifier le lien suivant afin de voir si des modifications n’ont pas été apportées dans les consignes : <https://github.com/BioDataScience-Course/BG_urchin>

## Objectifs

Ce projet est un travail en binôme à réaliser sur plusieurs modules.

Vous allez devoir compléter les fichiers qui se trouvent dans le dossier docs : 

- **urchin_notebook.Rmd** qui se trouve dans `docs/notebook/urchin_notebook.Rmd`
- **urchin_report.Rmd** qui se trouve dans `docs/report/urchin_report.Rmd`

Réalisez un carnet de laboratoire afin d'explorer les données sur la biométrie des oursins. 

Réalisez des régressions linéaires simples, multiples et polynomiales et des modèles linéaires pour étudier les données.

## Mise en situation

Les données employées dans le cadre de cette étude proviennent des recherches du professeur Philippe Grosjean portant sur la croissance de *Paracentrotus lividus* Lamarck (1816).

Vous pouvez importer les données via la fonctions suivantes :

```
urchin <- data.io::read("urchin_bio", package = "data.io")
```

N'hésitez pas à faire appel à la page d'aide de ce jeu de données

```
.?urchin_bio
```


