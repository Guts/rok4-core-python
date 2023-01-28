---
hide:
  - navigation
---

<div id="version_menu">
  <b>1.1.0</b>
  <a href="../">Documentation générale</a>
  <a href="../CHANGELOG/">Changements</a>
  <a href="../DOCUMENTATION/">Documentation développeur</a>
  <a href="../TESTS/">Rapport des tests</a>
</div>

# Changements

## Summary

Prise en charge de plusieurs clusters S3 de stockage.

## Changelog

### [Added]

* Librairie d'abstraction du stockage :
    * Prise en charge de plusieurs clusters S3. Les variables d'environnement pour le stockage S3 précisent plusieurs valeurs séparées par des virgules, et les noms des buckets peuvent être suffixés par "@{S3 cluster host}". Par défaut, le premier cluster défini est utilisé. L'hôte du cluster n'est jamais écrit dans le descripteur de pyramide ou le fichier liste (puisque stockés sur le cluster, on sait sur lequel sont les objets). Les objets symboliques ne le précisent pas non plus et ne peuvent être qu'au sein d'un cluster S3

<!-- 
### [Added]

### [Changed]

### [Deprecated]

### [Removed]

### [Fixed]

### [Security] 
-->
