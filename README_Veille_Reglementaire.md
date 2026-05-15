# 🛡️ Plateforme IA de Veille Réglementaire
### Direction : Risques Financiers

Ce projet consiste à concevoir et déployer une plateforme intelligente permettant d'automatiser la surveillance, l'analyse et la synthèse des évolutions normatives émises par les régulateurs financiers nationaux et internationaux. L'objectif est de transformer une veille manuelle chronophage en un outil d'aide à la décision proactif.

## 👥 Équipe Projet
* **LOUGMIRI Hamza** — [lougmirihamza.25@ump.ac.ma](mailto:lougmirihamza.25@ump.ac.ma)
* **SBABTI Brahim** — [ibrahimsbabti2@gmail.com](mailto:ibrahimsbabti2@gmail.com)
* **MAZROUI Oussama** — [oussamamazroui49@gmail.com](mailto:oussamamazroui49@gmail.com)
* **BADIOUI Asmaa** — [asmaa.badioui.ensao@ump.ac.ma](mailto:asmaa.badioui.ensao@ump.ac.ma)
* **HACHMI Hajar** — [hajar.hachmi.23@ump.ac.ma](mailto:hajar.hachmi.23@ump.ac.ma)
* **BENCHEIKH SENHAJI Salma** — [salma.bencheikhsenhaji.ensao@ump.ac.ma](mailto:salma.bencheikhsenhaji.ensao@ump.ac.ma)

---

## 🎯 Périmètre de Collecte (Sourcing)
Le système interroge de manière autonome les sources suivantes :
* **Sources Nationales :** Bank Al-Maghrib (BAM), Autorité Marocaine du Marché des Capitaux (AMMC).
* **Sources Européennes :** Autorité Bancaire Européenne (EBA), Banque Centrale Européenne (BCE).
* **Formats supportés :** PDF (Bulletins officiels, circulaires), HTML (articles Web) et documents textuels.

## 🚀 Spécifications Fonctionnelles
### 🧠 Module d'Extraction IA
* **Analyse Sémantique :** Identification des thématiques (Lutte anti-blanchiment, Solvabilité, ESG, etc.).
* **Synthèse Automatique :** Génération de "Flashs Réglementaires" concis (max 300 mots).
* **Données Clés :** Extraction automatique des dates d'application, seuils chiffrés et sanctions prévues.

### 📈 Analyse d'Impact & Interface
* **Calcul de Criticité :** Attribution d'un score de risque (Faible / Moyen / Élevé).
* **Classification Métier :** Orientation vers les départements Trésorerie, Crédit, Reporting, etc.
* **Recherche Intelligente :** Moteur de recherche sémantique basé sur le sens des questions.

## 🛠️ Spécifications Techniques
| Composant | Technologie Recommandée |
| :--- | :--- |
| **Backend** | Python (FastAPI) |
| **Moteur IA** | LLM avec architecture RAG (Retrieval-Augmented Generation) |
| **Base de Données** | PostgreSQL & Vector DB (Recherche sémantique) |
| **Frontend** | React ou Vue.js |

## 🔐 Sécurité & Confidentialité
* **Hébergement :** Serveurs sécurisés internes ou Cloud souverain.
* **Confidentialité :** Aucun texte interne n'est envoyé vers des serveurs IA publics non sécurisés.
* **Audit :** Journalisation de toutes les actions utilisateurs.

## 📅 Calendrier de Réalisation
* **Conception :** Spécifications détaillées & Maquettes ($T0+3$ semaines).
* **MVP :** Version beta - Source BAM uniquement ($T0+8$ semaines).
* **Finalisation :** Plateforme complète multi-sources ($T0+14$ semaines).
