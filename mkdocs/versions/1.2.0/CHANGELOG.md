---
hide:
  - navigation
---

<div id="version_menu">
  <b>1.2.0</b>
  <a href="../">Documentation générale</a>
  <a href="../CHANGELOG/">Changements</a>
  <a href="../DOCUMENTATION/">Documentation développeur</a>
  <a href="../TESTS/">Rapport des tests</a>
</div>

# Changements

## Summary

Ajout des librairies pour l'utilitaire make-layer.py

## Changelog

### [Added]

* Librairie Storage : complétion des tests unitaires

* Librairie Pyramid :
    * Ajout de getter sur les niveaux du haut et du bas

* Ajout de la librairie de gestion d'une couche Layer :
    * Chargement d'une couche depuis des paramètres
    * Chargement d'une couche depuis un descripteur
    * Écriture du descripteur au format attendu par le serveur
    * Écriture des tests unitaires

* Ajout d'une librairie d'utilitaires Utils
    * Conversion d'un SRS en objet OSR SpatialReference
    * Conversion d'une bbox en objet OGR Geometry
    * Reprojection d'une bbox avec densification des côtés et reprojection partielle
    * Écriture des tests unitaires

* Configuration de l'outil coverage pour voir la couverture des tests unitaires

<!-- 
### [Added]

### [Changed]

### [Deprecated]

### [Removed]

### [Fixed]

### [Security] 
-->
