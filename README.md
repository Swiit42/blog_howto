# Création du projet `blog` en mode tuto

## explication

On reprend, l'éternel, exercice du blog un de plus... :blush:

Ce projet est à disposition des apprenants afin de visualiser étape par étape la construction du blog

Chaque grande étape fera l'object d'une branche.

À l'issue de chaque branche, celle-ci  sera `merge` dans `develop`

`readme` avancera en même temps que les branches, il comprendra les commandes à effectuer et les modifications de fichier.

## Installation

__Stack__ :

- ruby 2.6.4
- rails 6.0.x
- sqlite3

Après avoir `clone` le projet, il vous faut renommer le fichier `database.yml.sample` en `database.yml`

rappel pour créer l'app :

```shell
$ rails new blog_howto
  create
  create  README.md
  create  Rakefile
  create  .ruby-version
  create  config.ru
  create  .gitignore
  create  Gemfile
  [...]
  yarn install
  [...]
  ✨  Done in 4.87s.
```
