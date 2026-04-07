# ProjetACF2L2026

> Projet de communication digitale — Aéro-Club de Frotey-Les-Lure (ACF2L)
> BTS SIO SLAM — Novembre 2024

---

## Contexte

L'**Aéro-Club de Frotey-Les-Lure (ACF2L)** est une association loi 1901, agréée Jeunesse et Sports, adhérente à la FFULM (Fédération Française d'ULM). Basée à Lure (70200), l'association assure la formation de pilotes et d'instructeurs ULM, et propose des prestations complémentaires : maintenance et montage d'ULM, restauration rapide, hébergement (studios et chambres) pour les élèves stagiaires, ainsi que la location d'emplacements en hangars.

Ce projet s'inscrit dans une stratégie de communication digitale initiée en 2020, visant à accroître la visibilité de l'association par la création d'un site internet. Le site vitrine initial, confié à la société Clarck à partir d'un template, nécessitait une finalisation puis une évolution vers un site dynamique permettant l'interaction avec le public et les adhérents.

## Objectifs

### Phase 1 — Site vitrine
- Présenter l'association : personnel, locaux, localisation et plan d'accès.
- Mettre en place un logo et une identité visuelle.
- Présenter les différents types d'ULM et le matériel disponible.
- Informer sur la réglementation (conditions de vol, diplômes de pilote/instructeur).
- Afficher les tarifs des prestations (baptêmes de l'air, heures de pilotage).
- Publier des photos des prestations réalisées.
- Fournir des liens vers les partenaires (FFULM, cartes aéronautiques, météo).

### Phase 2 — Site dynamique
- Mettre en place un formulaire de contact conforme au RGPD.
- Développer un système de réservation en ligne (cours, matériel, vols).
- Créer un espace membres avec historique des cours et réservations.
- Installer et configurer un serveur de base de données.

### Hébergement
- Héberger le site sur du matériel auto-géré (ordinateur reconditionné via le projet TAE — ATD Quart Monde / LaCollecte.tech).
- Respecter les obligations légales liées à l'hébergement de site web.

## Stack technique

| Domaine | Technologies |
|---|---|
| **Front-end** | HTML5, CSS3, JavaScript |
| **Back-end** | PHP |
| **Base de données** | MySQL |
| **Serveur** | Apache (LAMP) |
| **CMS / Template** | Template Awaiken (base initiale Clarck) |
| **Versioning** | Git / GitHub |

## Architecture

```
ProjetACF2L2026/
├── index.html              # Page d'accueil (site one-page avec rubriques)
├── assets/
│   ├── css/                # Feuilles de style
│   ├── js/                 # Scripts JavaScript
│   └── img/                # Ressources graphiques (photos, logo)
├── php/
│   ├── config.php          # Connexion BDD
│   └── traitement.php      # Traitement des formulaires
├── sql/
│   └── schema.sql          # Structure de la base de données
└── README.md
```

## Fonctionnalités développées

- **Site vitrine responsive** — Présentation complète de l'association en format one-page.
- **Formulaires dynamiques** — Réservation de vols et demandes d'informations avec validation côté client et serveur.
- **Base de données** — Stockage des soumissions, gestion des contacts et des réservations.
- **Conformité RGPD** — Mentions légales, consentement explicite, politique de traitement des données personnelles.

## Moyens mobilisés

- **Équipe** : groupe de 3 étudiants BTS SIO en stage dans l'association.
- **Matériel** : ordinateur reconditionné fourni par le projet TAE en partenariat avec LaCollecte.tech.
- **Budget client** : 5 000 € (ou équivalent en baptêmes de l'air).

## Concurrence identifiée

- [Aéro-club du Lys](http://www.aeroclubdulys.fr/)
- [Aériance](https://aeriance.fr/baptemes-paramoteur)
- [Adventure Paris Nord](https://adventure-paris-nord.com)

## Installation

```bash
git clone https://github.com/fred5551/ProjetACF2L2026.git
```

1. Configurer un environnement LAMP (Apache, MySQL, PHP).
2. Importer `sql/schema.sql` dans MySQL.
3. Renseigner les identifiants de connexion dans `php/config.php`.
4. Déployer les fichiers à la racine du serveur web.

## Auteur

Projet réalisé dans le cadre du **BTS SIO SLAM** — Novembre 2024.

## Crédits

- Template initial : [Awaiken Themes](https://awaikenthemes.com) — Licence CC BY-ND 4.0
- Icônes : [Font Awesome](https://fontawesome.io/), [Flaticon](https://www.flaticon.com/), [Linearicons](https://linearicons.com/free)
- Polices : [Google Fonts](https://fonts.google.com/)
- Images : [Unsplash](https://unsplash.com/), [Freepik](https://www.freepik.com/), [Pixabay](https://pixabay.com/)

## Licence

Template sous licence [Creative Commons BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0/).
Projet à usage éducatif.
