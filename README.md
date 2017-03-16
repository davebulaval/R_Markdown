# RMarkdown & outils de travail collaboratif

Présentation faite sous forme d'atelier optionnel offerte par l'école d'actuariat de l'Université Laval.

L'atelier consite en une présentation entrecoupée d'exemples et d'exercices. Les sujets traités sont R Markdown et les outils de travail collaboratifs.

***********************

## 17 mars 2017

La version du projet au 17 mars 2017 est celle présentée lors de l'atelier du jeudi 7 avril 2016 à l'Université Laval à Québec par Laurent Caron et modifier par Samuel Lévesque et David Beauchemin.

Présentateurs : Samuel Lévesque et David Beauchemin

### Préalables :

#### 1. Mise à jour de R

S'assurer d'avoir la version de R la plus à jour (3.3.3 — le numéro de version s'affiche au démarrage de R).

#### 2. Mise à jour de RStudio ou GNU Emacs

La formation sera beaucoup basée sur l'utilisation de RStudio, avec aussi des indications pour GNU Emacs. Assurez-vous d'avoir les versions les plus à jour de votre éditeur de texte favori. RStudio: 1.0.136. La distribution de GNU Emacs de Vincent Goulet: 24.5.1-modified-6.

#### 3. Installation du package rmarkdown

Depuis l'invite de commande de R, entrer

``` r
install.packages("rmarkdown")
```

Ceci installera également des packages dépendants.

#### 4. Installer TeX Live

> L'installation de TeX Live prend du temps! Procédez à l'installation
> avant la formation.

Certaines fonctionnalités de RMarkdown requièrent une installation de LaTeX. Nous recommandons la distribution TeX Live. Les capsules vidéo suivantes expliquent la procédure d'installation:

- [Installation sous Windows](https://www.youtube.com/watch?v=7MfodhaghUk&feature=youtu.be)
- [Installation sous macOS](https://www.youtube.com/watch?v=kA53EQ3Q47w&feature=youtu.be)


***********************
