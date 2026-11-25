# Diagnostic et Analyse Décisionnelle des Annulations de Réservations Hôtelières

**Projet d'Expertise Analytique et Décisionnelle — Secteur Tourisme et Hôtellerie**

* **Établissement :** École Supérieure de Technologie d'Oujda (ESTO) — Université Mohammed Premier
* **Filière :** Informatique Décisionnelle et Intelligence Artificielle (IDIA)
* **Année universitaire :** 2025 – 2026
* **Réalisé par :** Khaoula Bakraoui & Houda Bouyachouche (Groupe N° 10)
* **Encadrant :** M. Taha-Amine Miri

---

## 1. Contexte et Problématique

Dans l'industrie hôtelière, la maximisation du revenu (*Revenue Management*) repose sur un équilibre délicat entre le taux d'occupation et le tarif moyen journalier. L'essor des agences de voyage en ligne (*Online Travel Agencies* — OTA) et la généralisation des politiques d'annulation flexible ont fortement accru la volatilité des réservations, entraînant des pertes sèches de chiffre d'affaires et une complexification de la planification opérationnelle.

**Question décisionnelle :**  
> *Quels sont les facteurs déterminants qui expliquent la probabilité d'annulation d'une réservation hôtelière, et quels leviers opérationnels et tarifaires permettent de réduire ce risque ?*

### Objectifs de l'étude
1. Évaluer le taux d'annulation global et comparer la vulnérabilité selon la typologie d'établissement (*City Hotel* vs *Resort Hotel*).
2. Mesurer l'impact du délai d'anticipation (*Lead Time*) sur le comportement d'annulation.
3. Identifier les effets de saisonnalité mensuelle et le poids des canaux de distribution.
4. Traduire les résultats statistiques en recommandations concrètes d'aide à la décision.

---

## 2. Architecture du Dépôt

```text
hotel-booking-cancellation-analysis/
├── README.md                 # Documentation complète et synthèse décisionnelle
├── hotel_bookings.csv        # Jeu de données brut (source : Kaggle)
└── traitement.ipynb          # Notebook Jupyter : nettoyage, analyse exploratoire (EDA) et visualisations
