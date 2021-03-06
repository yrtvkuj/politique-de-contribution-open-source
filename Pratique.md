---
title: Meilleures Pratiques
layout: default
---

## Meilleures pratiques

### TL;DR

* Gestion des comptes personnels et d'organisations
* Inventaire des comptes d'organisation
* Distinction des contributions professionnelles / personnelles
* Aide au choix d'une plateforme de publication
* Aide au choix de la licence
* Diffusion initiale
* Suivi des anomalies
* Tests
* Gestion des versions
* Fichiers par défaut dans un repository
* Headers de fichiers source
* Gestion de la qualité
* Gestion de la communauté
* Outillage

### Gestion des comptes personnels et organisation

Utilisation de repository au sein de comptes d'organisation

Deux propriétaires par repository

### Inventaire des comptes d'organisation

Si sur Github, referencer le compte d'organisation comme un compte gouvernemental

### Distinction des contributions personnelles / Professionnelles

Utilisation du compte professionnel avec le mail en ```.gouv.fr```

Créer de repository, configurés de la manière suivante:

* Repository professionnel

`git config user.email <prenom.nom@ministere.gouv.fr>`

* Repository personnel

`git config user.email <email@perso.fr>`

Afin de vérifier que la commande a bien été prise en compte

`git config --get user.email`

### Aide au choix de la plateforme 

En plus du système de suivi de version de code source, une plateforme propose un ensemble d'outils collaboratifs associés et visent une communauté de développeurs.

Des exemples de plateformes possibles sont:
 * Github : https://github.com/
 * Gitlab : http://gitlab.com/
 * Framagit : http://framagit.org/ (gitlab)
 * Adullact : http://gitlab.adullact.net/ (gitlab)
 * FSFE: https://git.fsfe.org/ (gitea)
 * FSF : https://git.savannah.gnu.org (raw)

Certaines sont libres, d'autres publient leur données anonymisées en open-data, leur portée géographique peut varier... La liste est incomplète.

Par défaut, github offre la plus grande communuauté de développeurs au niveau international.

### Aide au choix de la licence

Le choix d'une licence est aussi le choix d'une communauté de developpeurs et d'un écosystème d'outils associés. Une fois la famille de licence déterminée, c'est avant tout la communauté visée qui doit déterminer le choix.

Sinon, les licences recommandées par défaut sont:
  * Permissive : Apache 2.0
  * Avec partage à l'identique : GNU GPL v3 (standard, lesser ou affero en fonction)

 > Multilicensing : il est possible de fournir un logiciel sous plusieurs licenses simultanément, bien que cela puisse entrainer de la confusion

### Gestion des versions

Avoir une politique de gestion des versions est recommandé. Le guide de versioning semantique (http://semver.org/) est un bon exemple à suivre.

### Fichiers présents dans le repository

Assurez-vous d'avoir au minimum les fichiers README, CONTRIBUTING and LICENSE.

* README: description du projet. Peut décrire l'objectif et l'administration à l'origine de la publication.

* CONTRIBUTING: guide de contribution, comment s'impliquer et identification du processus de contribution et des licences associées

* LICENSE: licence de publication du logiciel

* MAINTAINERS: liste des mainteneurs du projet (avec des droits de vote ou de commit généralement)

* ROADMAP: feuille de route publique

* CONDUCT: un code de conduite pour réguler la communauté de contributeurs. Des exemples peuvent être trouvés:  [https://www.djangoproject.com/conduct/](https://www.djangoproject.com/conduct/) et [https://github.com/18F/code-of-conduct](https://github.com/18F/code-of-conduct)

* GOVERNANCE: décrit la gouvernance du projet, les rôles et les drois de votes. Un exemple est le fichier 

* NFR: Choix d'architecture technique du projet qui ne correspondent pas à des exigences fonctionnelles.

Ces fichiers doivent être en texte simple ou avec du maruage minimum (ie Markdown). Il n'est pas recommandé d'utiliser des formats binaires (ie PDF)

### Sécurité

 * Outil de scan de sécurité
 * Guide de sécurité méthodologie agile ANSSI / DINSIC

### Outillage

Se référer à https://www.linuxfoundation.org/tools-managing-open-source-programs/#1 
