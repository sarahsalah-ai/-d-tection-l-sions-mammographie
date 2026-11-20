# Détection automatique de lésions par imagerie médicale (Mammographies)

Projet de fin d'études (PFE) de Master 2 en Automatique Industrielle portant sur la conception d'un pipeline automatisé d'analyse et de traitement d'images médicales appliqué aux mammographies, afin d'assister la détection de zones d'intérêt et de lésions de formes complexes.

## Objectifs du projet
* Automatiser le traitement de clichés mammographiques afin de faciliter l'identification de régions suspectes.
* Segmenter des zones d'intérêt présentant des contours irréguliers et des formes complexes.
* Extraire des caractéristiques pertinentes et réaliser une classification automatique pour distinguer les régions d'intérêt.

## Architecture du pipeline
1. **Prétraitement et amélioration d'image** : réduction du bruit, amélioration du contraste et préparation des images pour fiabiliser l'analyse.
2. **Segmentation** : isolement des zones d'intérêt (ROI) de formes complexes.
3. **Extraction de caractéristiques** : calcul de descripteurs permettant de caractériser les structures segmentées.
4. **Classification automatique** : prédiction / catégorisation à partir des caractéristiques extraites.

## Outils et technologies
* **Langages & environnements** : MATLAB, C++
* **Compétences clés** : traitement d'images, segmentation d'objets, analyse de formes complexes, structuration d'un pipeline automatisé.

## Structure du dépôt
* `src/` : scripts et codes sources du pipeline (prétraitement, segmentation, extraction, classification)
* `docs/` : notes méthodologiques, schémas ou présentations
* `README.md` : documentation du projet

## Auteure
**Sarah Salah** — Diplômée en Automatique Industrielle et actuellement en Traitement du Signal et des Images (M2 TSI).
