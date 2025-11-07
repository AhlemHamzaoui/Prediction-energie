# 🤖 Plateforme de Recrutement Intelligent

Ce projet consiste à développer une plateforme permettant de **faciliter le processus de recrutement** grâce à l'analyse intelligente des profils candidats et des offres d’emploi.  
Le système repose sur des techniques de **Machine Learning** et de **Traitement de Texte (NLP)** pour réaliser un **matching automatisé** entre les candidatures et les postes disponibles.

---

## 🎯 Objectifs du Projet

- Digitaliser et centraliser les informations des **candidats** et des **offres d’emploi**
- Extraire automatiquement les caractéristiques importantes des **CV**
- Évaluer la **pertinence** d’un candidat pour un poste donné
- Fournir un **score de compatibilité** clair et interprétable
- Faciliter la sélection des meilleurs profils par les recruteurs

---

## 🧱 Architecture Générale

| Module | Description |
|--------|-------------|
| Base de données (PostgreSQL) | Stockage des utilisateurs, entreprises, offres, et CV |
| Backend API (Java / Spring Boot ou FastAPI si Python) | Gestion des accès, traitement logique, scoring |
| Module NLP / ML | Extraction des informations et calcul du score de matching |

---

## 🔍 Fonctionnement

1. **Collecte des données**
   - Import des CV (PDF / texte)
   - Création des offres d’emploi

2. **Prétraitement texte (NLP)**
   - Nettoyage du texte (tokenisation, lemmatisation, stopwords)
   - Extraction des compétences & mots-clés importants

3. **Vectorisation**
   - TF-IDF ou Embeddings (selon version du projet)

4. **Calcul du Score de Compatibilité**
   - Similarité cosinus entre le CV et l’offre
   - Score final entre **0 et 100**

5. **Retour au recruteur**
   - Classement des candidats par score
   - Possibilité de filtrer / sauvegarder / annoter

---

## 🧠 Modèle utilisé

Le système de matching s’appuie sur :

- **TF-IDF Vectorizer** pour la représentation des textes
- **Similarité Cosinus** pour mesurer la proximité entre le CV et l’offre
- (Optionnel) **Entraînement supervisé** sur données annotées (si disponible)

Ce modèle est :
- Simple
- Rapide
- Interprétable par les recruteurs

---
---

## ✅ Avantages

- Gain de temps pour les équipes RH
- Classement automatique et objectif des candidatures
- Basé sur les compétences réelles extraites du CV
- Flexible & améliorable

---

## 🔮 Améliorations futures

- Ajout d'un modèle basé sur **BERT / Word Embeddings**
- Analyse du **niveau d'expérience** et des **certifications**
- Interface de visualisation avancée
- Intégration d’un chatbot d’assistance au candidat

---

## 👩‍💻 Réalisé par

**Ahlem Hamzaoui**  
Étudiante en Data Science & Intelligence Artificielle  
Année Universitaire 2024 / 2025



## 📂 Structure du Projet (exemple)

