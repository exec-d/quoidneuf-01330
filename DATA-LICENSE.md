# Licences des données

Ce dépôt redistribue des données publiques françaises et des données
OpenStreetMap. Les conditions diffèrent selon le jeu de données, et
s'appliquent à quiconque réutilise ce dépôt.

## Fichiers publiés

| Fichier | Licence | Pourquoi |
|---|---|---|
| `metadata.json` | Licence Ouverte 2.0 | Ne contient que des métadonnées de commune et de source |
| `health.json` | **ODbL 1.0** | Incorpore des positions et horaires OpenStreetMap |
| `public_services.json` | **ODbL 1.0** | Incorpore des positions et horaires OpenStreetMap |

L'ODbL est **contaminante pour la base dérivée** : un fichier qui incorpore
ne serait-ce qu'une position OSM est une base dérivée, et se redistribue sous
ODbL. C'est la raison pour laquelle les deux fichiers de module y passent
entièrement, alors que leurs sources majoritaires sont en Licence Ouverte.

## Sources

### FINESS — Structures
Agence du Numérique en Santé · Licence Ouverte 2.0
<https://www.data.gouv.fr/datasets/finess-structures-1>

### Annuaire Santé — RPPS
Agence du Numérique en Santé · Licence Ouverte 2.0
<https://www.data.gouv.fr/datasets/annuaire-sante-extractions-des-donnees-en-libre-acces-des-professionnels-intervenant-dans-le-systeme-de-sante-rpps>

### Géo'DAE — Base nationale des défibrillateurs
Ministère de la Santé · Licence Ouverte 2.0
<https://www.data.gouv.fr/datasets/geodae-base-nationale-des-defibrillateurs>

### Annuaire de l'administration — Base de données locales
Direction de l'information légale et administrative (DILA) · Licence Ouverte 2.0
<https://www.data.gouv.fr/datasets/service-public-gouv-fr-annuaire-de-ladministration-base-de-donnees-locales>

### Réseau La Poste
La Poste · Licence Ouverte 2.0
<https://www.data.gouv.fr/datasets/liste-des-bureaux-de-poste-agences-postales-et-relais-poste>

### OpenStreetMap
© les contributeurs OpenStreetMap · **ODbL 1.0**
<https://www.openstreetmap.org/copyright>

## Réutilisation

La Licence Ouverte 2.0 demande la mention de la source **et de la date de
mise à jour** ; celle-ci vit dans `metadata.json`, champ `generated_at`.

L'ODbL demande l'attribution, le partage à l'identique de la base dérivée et
l'absence de mesures techniques restreignant la réutilisation.
