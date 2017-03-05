# Outils de travail collaboratif

Présentation faite sous forme d'atelier optionnel dans le cadre du cours ACT-2002 : Méthodes numériques en actuariat à l'Université Laval.

L'atelier consite en une présentation entrecoupée d'exemples et d'exercices. Les sujets traités sont R Markdown et le système Git.

***********************

## 7 avril 2016

La version du projet au 7 avril 2016 est celle présentée lors de l'atelier du jeudi 7 avril 2016 à l'Université Laval à Québec.

Présentateurs : Laurent Caron et Vincent Goulet

### Préalables :

#### 1. Mise à jour de R

S'assurer d'avoir la version de R la plus à jour (3.2.4 — le numéro de version s'affiche au démarrage de R).

#### 2. Mise à jour de RStudio ou GNU Emacs

La formation sera beaucoup basée sur l'utilisation de RStudio, avec aussi des indications pour GNU Emacs. Assurez-vous d'avoir les versions les plus à jour de votre éditeur de texte favori. RStudio: 0.99.893. La distribution de GNU Emacs de Vincent Goulet: 24.5.1-modified-6.

#### 3. Installation du package rmarkdown

Depuis l'invite de commande de R, entrer

``` r
install.packages("rmarkdown")
```

Ceci installera également des packages dépendants.

#### 4. Installer TeX Live

Certaines fonctionnalités de RMarkdown requièrent une installation de TeX. Nous recommandons la distribution TeX Live. Les capsules vidéo suivantes expliquent la procédure d'installation (simple mais longue, vu la taille de la distribution):

[Installation sous Windows](https://www.youtube.com/watch?v=z_dq3dns-WU)

[Installation sous OS X](https://www.youtube.com/watch?v=fjcR6lFy0c4)

#### 5. Installation de Git

Vous aurez besoin du système de contrôle de version Git.

##### Windows :

Installer à partir de https://git-scm.com/downloads

##### Mac OS X :

Nous recommandons d'installer les outils de développement d'Apple. C'est un peu plus complexe au départ, mais plus simple à long terme. Tout d'abord installer XCode depuis le App Store. Ensuite, ouvrir l'application Terminal (dans Applications -> Utilitaires) et essayer d'exécuter la commande

``` git
git
```

Si git n'est pas disponible, cela devrait vous offrir d'installer les Command Line Tools. Suivre les indications. Vous pouvez aussi lancer l'installation avec 

``` git
xcode-select --install
```
***********************