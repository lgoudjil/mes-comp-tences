---
name: Conception de modèle en étoile Power BI
category: personal
level: expert
description: Conception de modèles sémantiques Power BI basés sur un schéma en étoile, optimisés pour la performance et compatibles MCP Server.
tools_allowed:
  - Power BI Desktop
  - Tabular Editor
  - SQL Server / Azure SQL
  - Microsoft Fabric Lakehouse
---

## Objectif
Concevoir des modèles de données Power BI clairs, performants et stables en utilisant le **schéma en étoile**, compréhensible par les utilisateurs métiers et exploitable par des agents MCP.

## Compétences maîtrisées
- Identification des tables de faits et de dimensions
- Définition de la granularité des données
- Création de hiérarchies métier
- Gestion des dimensions conformes
- Mise en place de tables de dates dédiées

## Règles de conception
- Une table de faits = une seule granularité
- Relations *plusieurs-à-un* uniquement
- Sens de filtre simple par défaut
- Éviter les snowflakes inutiles

## Compatibilité MCP
- Structure explicite et normalisée
- Nommage clair des tables et colonnes
- Sémantique stable et déterministe

