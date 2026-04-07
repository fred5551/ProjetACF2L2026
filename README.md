# ProjetACF2L2026

> **Projet de communication digitale — Aéro-Club de Frotey-Les-Lure (ACF2L)**  
> BTS SIO SLAM — Novembre 2024 — Travail en trinôme

---

## 📋 Contexte

L'**Aéro-Club de Frotey-Les-Lure (ACF2L)** est une association loi 1901, agréée Jeunesse et Sports, adhérente à la FFULM (Fédération Française d'ULM). Basée à Lure (70200), l'association assure la formation de pilotes et d'instructeurs ULM, et propose des prestations complémentaires : maintenance et montage d'ULM, restauration rapide, hébergement (studios et chambres) pour les élèves stagiaires, ainsi que la location d'emplacements en hangars.

Ce projet s'inscrit dans une stratégie de communication digitale initiée en 2020, visant à accroître la visibilité de l'association par la création d'un site internet. Le site vitrine initial, confié à la société Clarck à partir d'un template, nécessitait une finalisation puis une évolution vers un site dynamique permettant l'interaction avec le public et les adhérents.

---

## 🎯 Objectifs

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

---

## 👥 Organisation du travail en mode projet

Ce projet a été réalisé **en trinôme**. Pour organiser le travail, répartir les tâches et assurer le suivi de l'état d'avancement du site, nous avons utilisé **Trello** comme outil de gestion de projet avec un tableau Kanban structuré en 3 colonnes :

| Colonne      | Rôle                                                     |
| ------------ | -------------------------------------------------------- |
| **À FAIRE**  | Tâches identifiées mais non encore démarrées             |
| **EN COURS** | Tâches en cours de réalisation par un membre de l'équipe |
| **TERMINÉE** | Tâches achevées et validées par l'équipe                 |

Chaque carte Trello contenait :

- La **description détaillée** de la tâche à réaliser (ex : « Modifier le code du site »)
- Le **membre assigné** (identification claire du responsable)
- Les **pièces jointes** (fichiers livrés, captures d'écran)
- Les **commentaires** pour le suivi et la traçabilité des échanges

### Tableau Trello — Vue d'ensemble

![Tableau Trello du projet ACF2L](Capture%20d'écran%202026-04-08%20003222.png)

### Carte Trello — Détail d'une tâche

![Détail d'une carte Trello — Modifier le code du site](Capture%20d'écran%202026-04-08%20003527.png)

> **Compétence E validée** — _Travailler en mode projet_ : analyse des objectifs, planification des activités via Trello (Kanban), répartition des tâches entre les 3 membres, suivi de la progression et évaluation de l'état d'avancement.

Le versioning du code a été assuré par **Git et GitHub**, permettant à chaque membre de travailler sur ses fichiers sans conflit, avec un historique complet des modifications.

---

## 🛠️ Stack technique

| Domaine               | Technologies                            |
| --------------------- | --------------------------------------- |
| **Front-end**         | HTML5, CSS3, JavaScript                 |
| **Back-end**          | PHP                                     |
| **Base de données**   | MySQL                                   |
| **Serveur**           | Apache (LAMP)                           |
| **CMS / Template**    | Template Awaiken (base initiale Clarck) |
| **Versioning**        | Git / GitHub                            |
| **Gestion de projet** | Trello (Kanban)                         |

---

## 📁 Architecture du projet

```
ProjetACF2L2026/
├── index.html              # Page d'accueil (site one-page avec rubriques)
├── css/                    # Feuilles de style
├── js/                     # Scripts JavaScript
├── fonts/                  # Polices personnalisées
├── images/                 # Ressources graphiques (photos, logo)
├── licence.txt             # Licence du template
├── SyntheseSite_Mission1.pdf   # Document de synthèse des modifications
└── README.md
```

---

## ✅ Fonctionnalités développées

- **Site vitrine responsive** — Présentation complète de l'association en format one-page.
- **Formulaires dynamiques** — Réservation de vols et demandes d'informations avec validation côté client et serveur.
- **Base de données** — Stockage des soumissions, gestion des contacts et des réservations.
- **Conformité RGPD** — Mentions légales, consentement explicite, politique de traitement des données personnelles.
- **Logo personnalisé** — Création et intégration d'un logo pour l'identité visuelle de l'association.
- **Widget météo** — Intégration d'un widget de météo aéronautique pour la sécurité des pilotes.

---

## 📄 Document de synthèse

Le document de synthèse des modifications apportées au site est consultable ici :

📎 [SyntheseSite_Mission1.pdf](SyntheseSite_Mission1.pdf)

---

## 🏗️ Moyens mobilisés

- **Équipe** : trinôme de 3 étudiants BTS SIO SLAM.
- **Gestion de projet** : Trello (Kanban) pour la planification et le suivi.
- **Versioning** : Git / GitHub pour la collaboration et l'historique du code.
- **Matériel** : ordinateur reconditionné fourni par le projet TAE en partenariat avec LaCollecte.tech.
- **Budget client** : 5 000 € (ou équivalent en baptêmes de l'air).

---

## 🔗 Concurrence identifiée

- [Aéro-club du Lys](http://www.aeroclubdulys.fr/)
- [Aériance](https://aeriance.fr/baptemes-paramoteur)
- [Adventure Paris Nord](https://adventure-paris-nord.com)

---

## 🚀 Installation

```bash
git clone https://github.com/fred5551/ProjetACF2L2026.git
```

1. Configurer un environnement LAMP (Apache, MySQL, PHP).
2. Importer le schéma SQL dans MySQL.
3. Renseigner les identifiants de connexion dans la configuration PHP.
4. Déployer les fichiers à la racine du serveur web.

---

## 🎓 Compétences BTS SIO mobilisées

| Compétence                 | Description                                       | Application dans le projet                            |
| -------------------------- | ------------------------------------------------- | ----------------------------------------------------- |
| **D** — Présence en ligne  | Développer la présence en ligne de l'organisation | Site web publié pour l'association ACF2L              |
| **E** — Mode projet        | Travailler en mode projet                         | Trinôme, Trello (Kanban), Git, répartition des tâches |
| **F** — Mise à disposition | Mettre à disposition un service informatique      | Site fonctionnel livré avec hébergement auto-géré     |
| **G** — Développement pro  | Organiser son développement professionnel         | Apprentissage LAMP, travail collaboratif, RGPD        |

---

## ✍️ Auteur

Projet réalisé dans le cadre du **BTS SIO SLAM** — Novembre 2024.

## 📝 Crédits

- Template initial : [Awaiken Themes](https://awaikenthemes.com) — Licence CC BY-ND 4.0
- Icônes : [Font Awesome](https://fontawesome.io/), [Flaticon](https://www.flaticon.com/), [Linearicons](https://linearicons.com/free)
- Polices : [Google Fonts](https://fonts.google.com/)
- Images : [Unsplash](https://unsplash.com/), [Freepik](https://www.freepik.com/), [Pixabay](https://pixabay.com/)

## 📜 Licence

Template sous licence [Creative Commons BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0/).  
Projet à usage éducatif.
