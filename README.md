# TheView

Une application de connaissance centralisée :

## Des notes
- Editeur Markdown
- Des liens entre notes
- Une arborescence de dossiers

### Éditeur
- compatible Markdown
- possibilité de switch entre rendu et source

### Mise en forme 
- titres
- souligné
- gras
- barré
- couleur
- surligné
- séparateur
- image
- Deux colonnes

## Fonctionnalités 
- palette de commande
- fuzzy search
- snippets

## Types de contenu
- On peut définir un type de contenu (un ensemble de champs prédéfinis personnalisés)
- on peut appliquer un ou plusieurs types de contenu a une note, ce qui lui attache leurs propriétés 
- pour créer un nouveau contenu d'un certain type, on crée une nouvelle note, on lui attribue un type, et on renseigne les propriétés

### Type de champs disponibles
- Coordonnées
- Date
- Date / Heure
- Texte (long)
- Texte (court)
- Nombre (simple)
- Nombre (note)
- Nombre (slider)
- Nombre (durée)
- Toggle
- Fichier Externe (upload)
- Choix (inline)
- Choix (dropdown)
- Choix (radio)
(la source des choix est alimentée par une table d'un type de contenu)

### Formulaires 
- par défaut, chaque type de contenu possède un formulaire de création qui permet créer de nouvelles notes de ce type
- Chaque type de contenu possède également un formulaire de modification pour éditer les propriétés des notes déjà créés de ce type
- le formulaire de modification peut être désactivé pour ne servir que d'affichage des propriétés 

### Tables
- par défaut, chaque type de contenu possède une vue "table", qui permet de lister les notes de ce type et leurs propriétés
- les tables peuvent être triées
- les tables peuvent être filtrées

### Intégration 
- il est possible d'intégrer dans une note des formulaires ou des tables
- il est possible de passer des paramètres aux formulaires et aux tables (un tri, un filtre, une valeur par défaut etc.)

### Tables particulières 
ces tables sont présentes par défaut et ne nécessitent pas un type de contenu particulier :
- notes modifiées récemment
- notes d'un dossier particulier
- notes à une note à X profondeur

### Type de contenu particulier 
- Projet : il propose une vue kanban plutôt que table


## Technologies
- [Mantine](https://mantine.dev/core/stack/)
- [TypeScript](https://www.typescriptlang.org/)
- [Supabase](https://supabase.com/docs)



