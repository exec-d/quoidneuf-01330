# quoidneuf-01330 — Villars-les-Dombes

Données locales de **Villars-les-Dombes** (code INSEE `01443`, code postal `01330`) publiées pour
l'application **QuoiD'Neuf**.

Ce dépôt ne contient aucun code métier : uniquement des faits, des APK et une page de présentation.
Chaque mise à jour est un commit lisible — c'est ce qui rend l'historique auditable et permet de
répondre à « quand ce service a-t-il changé d'horaires ? ».

## Contenu

| Fichier | Rôle |
|---|---|
| `metadata.json` | commune, modules disponibles, sources et fraîcheur |
| `health.json` | module Santé — médecins, pharmacies, hôpitaux, EHPAD, centres de santé, défibrillateurs |
| `public_services.json` | module Services publics — mairie, poste, France Services, gendarmerie, pompiers, bibliothèque |
| `app/latest.json` | dernière version de l'application publiée |

Les données sont extraites automatiquement chaque jour depuis l'Open Data national. Une extraction
qui ne change rien ne produit aucun commit.

## Sources et licences

Les données proviennent de FINESS et de l'Annuaire Santé (Agence du Numérique en Santé), de Géo'DAE,
de l'Annuaire de l'administration (DILA) et d'OpenStreetMap.

Voir `DATA-LICENSE.md` pour les mentions jeu par jeu — **Licence Ouverte 2.0** pour les sources
publiques françaises, **ODbL 1.0** pour les fichiers incorporant des éléments d'OpenStreetMap.

## L'application

Le moteur et le pipeline d'extraction vivent dans un dépôt séparé. L'application est distribuée en
APK Android signé via les *Releases* de ce dépôt.
