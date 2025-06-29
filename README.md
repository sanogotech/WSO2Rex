# WS2O  Rex



# 🚀 **Évolution vers une Plateforme Self-Service avec WSO2 API Manager à la SACEM**

**🎙️ Présenté par : Johan Brelet, Architecte Système Principal, SACEM**
📍 *WSO2 Oxygenate France 2025*

---

## 🧭 **Contexte et Enjeux**

La SACEM (Société des Auteurs, Compositeurs et Éditeurs de Musique) a pour mission de gérer et redistribuer les droits d’auteur dans le secteur musical. Sa transformation numérique a nécessité une modernisation profonde de ses échanges inter-applicatifs. Le système initial, largement **on-premise**, manquait de flexibilité, de gouvernance API centralisée, et de scalabilité.

L’objectif :
👉 Créer une **plateforme d’API Management moderne, gouvernée, sécurisée et scalable**, intégrée dans une **organisation agile** avec des équipes produits autonomes et orientées **valeur métier**.

---

## 🛠️ **Étapes Clés de la Transformation (2018 – 2025)**

| **Année**     | **Étape Clé**                              | **Contenu / Résultat**                                             |
| ------------- | ------------------------------------------ | ------------------------------------------------------------------ |
| **2018**      | Début de la mise en place WSO2             | Cadrage, choix de l’architecture, premiers POC                     |
| **2019-2020** | Structuration de la gouvernance            | Création d’une équipe transverse dédiée aux APIs                   |
| **2020**      | Déploiement haute disponibilité            | Architecture redondante, monitoring, SLA                           |
| **2021**      | Passage à l’**agilité à l’échelle (SAFe)** | Intégration API dans les équipes produits                          |
| **2022**      | Intégration CI/CD                          | Automatisation des tests, des déploiements, des contrôles          |
| **2023-2024** | Ouverture vers le **self-service**         | Portail API, Workflows de publication et validation                |
| **2025**      | Objectifs d’évolution                      | Conteneurisation on-premise, montée de version 4.3, intégration IA |

---

## 🔁 **Processus End-to-End de Publication API**

1. **Demande métier** par une équipe produit
2. **Design de l’API** via Swagger/OpenAPI
3. **Soumission au portail API self-service**
4. **Validation via un workflow automatisé**
5. **Tests automatiques (unitaires, intégration, sécurité)**
6. **Déploiement CI/CD** (GitLab, Jenkins, etc.)
7. **Publication dans le portail développeur** (avec documentation et SDK)
8. **Surveillance & Monitoring** (WSO2 Analytics, Prometheus, Grafana)
9. **Versioning et évolution continue**

---

## ✅ **Bonnes Pratiques Retenues par la SACEM**

| 🌟 **Pratique**              | ✅ **Application**                          |
| ---------------------------- | ------------------------------------------ |
| API First                    | Design systématique avant le développement |
| Self-Service avec garde-fous | Autonomie métier mais validation stricte   |
| Intégration CI/CD            | Qualité, sécurité et vélocité              |
| Documentation systématique   | Swagger, portails, SDK                     |
| Haute disponibilité          | Load balancing, redondance active          |
| Sécurité intégrée            | OAuth2, scopes, throttling, audit          |
| Culture DevSecOps            | Shift left sécurité dans les pipelines     |
| Mesure de la valeur métier   | Scorecards produit/API, analytics métier   |

---

## 📊 **Chiffres Clés**

| Indicateur                           | Valeur                          |
| ------------------------------------ | ------------------------------- |
| APIs en production                   | +150                            |
| Requêtes par mois                    | 80 millions                     |
| Temps moyen de publication d’une API | < 2 jours (vs 2 semaines avant) |
| Portail API                          | +30 équipes utilisatrices       |
| Taux d’APIs utilisées vs exposées    | 75% (fort taux d’usage réel)    |

---

## 🧪 **Cas Pratiques Internes**

### 🎵 Cas 1 : Exposition des catalogues d'œuvres

* Objectif : Permettre à des partenaires d'accéder aux catalogues en temps réel
* Réalisation : API publique REST sécurisée avec token à durée de vie courte
* Résultat : Diminution des appels manuels, meilleur SLA

### 💰 Cas 2 : Interconnexion avec les outils financiers

* API pour remonter les droits dus, automatiser les paiements
* Intégrée à SAP, sécurisée via scopes OAuth
* Réduction des erreurs de facturation et délais de traitement

### 🤝 Cas 3 : Collaboration externe via API Partners

* Partenaires (Spotify, YouTube...) intègrent les APIs de la SACEM
* API versionnées, quotas, supervision dédiée
* +20 partenaires connectés

---

## 🔮 **Perspectives et Roadmap 2025+**

1. **Conteneurisation complète on-premise**

   * Objectif : scalabilité, portabilité, agilité
   * Outils : Kubernetes, Helm, Istio

2. **Montée de version vers WSO2 API Manager 4.3**

   * Nouvelles fonctionnalités : GraphQL support, event-driven APIs, meilleure UX

3. **Intégration de l’IA**

   * Analyse comportementale des consommateurs d’API
   * Recommandation automatique d’APIs aux développeurs
   * Détection des usages suspects ou inefficaces

---

## 📘 **Retour d’Expérience (REX) de Johan Brelet**

> “La clé du succès n’a pas été uniquement l’outil. C’est l’**organisation** autour de l’outil, la **vision produit**, et surtout la **capacité à allier autonomie des équipes et gouvernance centralisée**. On est passés d’un système rigide à une **usine à API**, gouvernée mais agile.”

---

## 🏁 **Conclusion**

La SACEM démontre qu’un **API Management bien structuré avec WSO2** permet de :

* Donner de l’agilité aux équipes
* Garantir la sécurité et la conformité
* Favoriser la réutilisation des actifs numériques
* Accélérer la transformation numérique par la gouvernance API

Le passage au **self-service encadré**, soutenu par une plateforme robuste et une culture DevSecOps, permet aujourd’hui d’**industrialiser la consommation et la création d’API**, tout en conservant la maîtrise et la performance de la DSI.

---

## 📎 **Ressources Complémentaires**

* 🔗 [WSO2 API Manager Documentation](https://apim.docs.wso2.com/)
* 📘 Livre blanc SACEM : “Transformer son SI avec une stratégie API First”
* 🎥 [Vidéo YouTube : WSO2 Oxygenate 2025 – SACEM](https://youtu.be/JVBv9LzAAss?si=fF9GsDoYLnd1AKNs)

Souhaitez-vous une version **PowerPoint / PDF prête à présenter** ou un modèle de **plan de migration vers WSO2 pour un autre SI** ?
