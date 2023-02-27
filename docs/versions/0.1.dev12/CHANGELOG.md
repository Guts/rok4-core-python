---
hide:
  - navigation
---

<div id="version_menu">
  <b>0.1.dev12</b>
  <a href="../">Documentation générale</a>
  <a href="../CHANGELOG/">Changements</a>
  <a href="../DOCUMENTATION/">Documentation développeur</a>
  <a href="../TESTS/">Rapport des tests</a>
</div>

# Changements
## Summary

Amélioration de la CI avec passage sous poetry.

## Changelog

### [Added]

* Gestion du projet (compilations, dépendances...) via poetry
* Injection de la version dans le fichier `pyproject.toml` et `__init__.py` (définition de la variable `__version__`)
* Évolution de la CI github
    * Vérification des installations et tests unitaires sous python 3.7, 3.8, 3.9 et 3.10, sous ubuntu 20.04 et ubuntu 22.04
    * Publication de l'artefact avec les résultats des tests unitaires
    * Nettoyage de la release en cas d'erreur
    * Compilation de la documentation et publication sur la branche gh-pages

<!-- 
### [Added]

### [Changed]

### [Deprecated]

### [Removed]

### [Fixed]

### [Security] 
-->
