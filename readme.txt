# ProjetACF2L2026

> Projet de communication digitale réalisé dans le cadre du BTS SIO SLAM — Novembre 2024

---

## Contexte

Ce projet s'inscrit dans la stratégie de communication digitale de l'association **ACF2L**, visant à développer sa visibilité en ligne par la mise en place d'un site internet dynamique. Le site vitrine initial, conçu par la société Clarck à partir d'un template, nécessitait une finalisation et une évolution vers un site interactif permettant les échanges avec le public et les adhérents.

## Objectifs

- Finaliser et corriger le site vitrine existant.
- Mettre en place un **serveur d'hébergement** auto-géré (matériel reconditionné via le projet TAE — ATD Quart Monde / LaCollecte.tech).
- Déployer le site sur ce serveur en respectant les obligations légales d'hébergement.
- Développer les fonctionnalités dynamiques : **formulaires de réservation / contact**, stockage en base de données.
- Assurer la conformité **RGPD** des formulaires de collecte de données.

## Stack technique

| Domaine | Technologies |
|---|---|
| **Front-end** | HTML5, CSS3, JavaScript |
| **Back-end** | PHP |
| **Base de données** | MySQL |
| **Serveur** | Apache (LAMP) |
| **Versioning** | Git / GitHub |

## Architecture

```
ProjetACF2L2026/
├── index.html              # Page d'accueil
├── assets/
│   ├── css/                # Feuilles de style
│   ├── js/                 # Scripts JS
│   └── img/                # Ressources graphiques
├── php/
│   ├── config.php          # Connexion BDD
│   └── traitement.php      # Traitement des formulaires
├── sql/
│   └── schema.sql          # Structure de la base de données
└── README.md
```

## Fonctionnalités développées

- **Site vitrine** — Présentation de l'association, activités et actualités.
- **Formulaires dynamiques** — Réservation de vols et demandes d'informations avec validation côté client et serveur.
- **Base de données** — Stockage des soumissions, gestion des contacts et des réservations.
- **Conformité RGPD** — Mentions légales, consentement explicite, politique de traitement des données.

## Moyens mobilisés

- **Équipe** : groupe de 3 étudiants BTS SIO (stage en association).
- **Matériel** : ordinateur reconditionné fourni par le projet TAE en partenariat avec LaCollecte.tech.

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

## Licence

Projet à usage éducatif.
LICENSE:

This template released under the Creative Commons Attribution-NoDerivatives 4.0 International License ( https://creativecommons.org/licenses/by-nd/4.0/ ) This means that you are free:

	Share — copy and redistribute the material in any medium or format
	for any purpose, even commercially.
	
	Under the following terms:

	Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

	NoDerivatives — If you remix, transform, or build upon the material, you may not distribute the modified material.
	
	You must include a credit link to our website( https://awaikenthemes.com ) somewhere on
	your site. We like the footer credit that comes with the template. But you can also move to another place.
	

For removing our credit link: Read more here - https://awaikenthemes.com/license


These Terms of Service or license are subject to change at any time, without prior notice. 

====================================================================


SOURCES AND CREDITS:

Fonts:
	https://fonts.google.com/

Icons:
	http://fontawesome.io/
	https://www.flaticon.com/
	https://linearicons.com/free
	http://themes-pixeden.com/font-demos/7-stroke/

Stock Photos and Graphics:
	https://unsplash.com/
	https://www.freepik.com/
	https://pixabay.com/
 
Javascript Files:

	http://jquery.com/
	http://modernizr.com/
	http://imakewebthings.com/jquery-waypoints/
	https://owlcarousel2.github.io/OwlCarousel2/
	https://github.com/alicelieutier/smoothScroll
	http://dimsemenov.com/plugins/magnific-popup/



====================================================================


Thanks for downloading from https://awaikenthemes.com
