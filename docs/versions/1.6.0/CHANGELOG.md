---
hide:
  - navigation
---

<div id="version_menu">
  <b>1.6.0</b>
  <a href="../">Documentation générale</a>
  <a href="../CHANGELOG/">Changements</a>
  <a href="../DOCUMENTATION/">Documentation développeur</a>
  <a href="../TESTS/">Rapport des tests</a>
</div>

# Changements

## Summary

Lecture par système de fichier virtuel avec GDAL

## Changelog

### [Added]

* Storage
    * Fonction `get_osgeo_path` permettant de configurer le bon sytème de fichier virtuel en fonction du chemin fourni, et retourne celui à utiliser dans le Open de gdal ou ogr

### [Changed]

* Storage
    * la récupération d'un client S3 (`__get_s3_client`) permet de récupérer le client, l'hôte, les clés d'accès et secrète, ainsi que le nom du bucket sans l'éventuel hôte du cluster

### [Fixed]

* Storage
    * Lecture binaire S3 : mauvaise configuration du nom du bucket et de l'objet et mauvaise lecture partielle

### [Removed]

* Exceptions
    * `NotImplementedError` est une exceptions native
<!--
### [Added]

### [Changed]

### [Deprecated]

### [Removed]

### [Fixed]

### [Security]
-->
