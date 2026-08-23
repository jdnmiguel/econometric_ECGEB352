---
title: "Introduction à l'économétrie"
date: "Printemps 2026"
output:
  pdf_document:
    toc: false
    number_sections: false
geometry: margin=1in
fontsize: 11pt
---

# Organisation du cours

**Enseignant(s) :** *À compléter*  
**Email :** *À compléter*  
**Organisation :** 12 séances.

# Description du cours

Ce cours propose une introduction aux méthodes fondamentales de l'économétrie et à leur mise en œuvre avec **R**. Il vise à donner aux étudiants les outils nécessaires pour analyser des données économiques, estimer et interpréter des modèles de régression, réaliser des tests statistiques et comprendre les principales méthodes d'identification causale utilisées en économie empirique. Une attention particulière est portée à la reproductibilité des analyses et à l'interprétation économique des résultats.

Chaque séance combine des éléments théoriques, des illustrations empiriques et des applications sous **R**.

# Logiciels

- **R** et **RStudio**. Les étudiants devront installer les dernières versions de **R** et **RStudio** avant le premier cours.
- Une connaissance élémentaire de **R Markdown** est recommandée.

# Prérequis

Connaissances de base en statistiques descriptives et en économie.

# Supports pédagogiques

Les diapositives de cours, les jeux de données et les scripts **R** seront mis à disposition au fur et à mesure du semestre.

Les principaux ouvrages de référence sont :

- *Introduction to Econometrics with R*
- *Mastering Metrics* (Angrist & Pischke)
- *ModernDive*
- *R for Data Science*

Les lectures indiquées en **gras** sont **fortement recommandées**.

# Plan du cours

## Séance 1 : Introduction

**Contenu**

- Qu'est-ce que l'économétrie ?
- Corrélation et causalité
- Introduction à R
- La « Credibility Revolution » en économie empirique

**Lectures recommandées**

- **Sections 1.1 et 1.2, *Introduction to Econometrics with R***
- **Introduction, *Mastering Metrics***
- **Angrist & Pischke (2010), *The Credibility Revolution in Empirical Economics***

---

## Séances 2 et 3 : Manipulation, visualisation et description des données

**Contenu**

- Manipulation des données avec le *tidyverse*
- Nettoyage des données
- Statistiques descriptives
- Visualisation graphique des données

**Lectures recommandées**

- **Chapitre « Data Transformation », *R for Data Science***
- **Schwabish (2014), *An Economist's Guide to Visualizing Data***
- Chapitres 2 et 3 de *ModernDive*

---

## Séance 4 : Régression linéaire simple

**Contenu**

- Le modèle de régression linéaire simple
- Estimation par les moindres carrés ordinaires (MCO)
- Interprétation des coefficients
- Qualité de l'ajustement

**Lectures recommandées**

- **Chapitre 3, *Introduction to Econometrics with R***
- Chapitre 5 de *ModernDive*

---

## Séance 5 : Introduction à la causalité

**Contenu**

- Résultats potentiels
- Raisonnement contrefactuel
- Effet moyen d'un traitement
- Identification des effets causaux

**Lectures recommandées**

- **Chapitre 7, *Introduction to Econometrics with R***
- **Chapitre 1, *Mastering Metrics***
- Cunningham, *Causal Inference: The Mixtape*
- Morgan & Winship (2015)

---

## Séance 6 : Régression linéaire multiple

**Contenu**

- Régression multiple
- Variables de contrôle
- Biais de variable omise
- Interprétation des coefficients

**Lectures recommandées**

- **Chapitre 4, *Introduction to Econometrics with R***
- **Chapitre 2, *Mastering Metrics***
- Chapitre 6 de *ModernDive*

---

## Séance 7 : Échantillonnage

**Contenu**

- Échantillonnage aléatoire
- Distributions d'échantillonnage
- Introduction au bootstrap

**Lectures recommandées**

- **Chapitre 7 de *ModernDive***

---

## Séance 8 : Intervalles de confiance et tests d'hypothèses

**Contenu**

- Inférence statistique
- Intervalles de confiance
- Tests d'hypothèses
- Valeurs *p*

**Lectures recommandées**

- **Chapitres 8 et 9 de *ModernDive***

---

## Séance 9 : Inférence en régression

**Contenu**

- Erreurs standards
- Significativité statistique
- Intervalles de confiance
- Tests sur les coefficients de régression

**Lectures recommandées**

- **Chapitre 6, *Introduction to Econometrics with R***
- **Chapitre 10 de *ModernDive***

---

## Séance 10 : La méthode des doubles différences (*Differences-in-Differences*)

**Contenu**

- Estimateur en doubles différences
- Hypothèse de tendances parallèles
- Effets fixes
- Applications empiriques

**Lectures recommandées**

- **Chapitre 5, *Mastering Metrics***
- **Card & Krueger (1994), « Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania »**

---

## Séance 11 : Régression sur discontinuité

**Contenu**

- Discontinuité franche et floue
- Hypothèses d'identification
- Estimation et interprétation
- Applications empiriques

**Lectures recommandées**

- **Chapitre 4, *Mastering Metrics***
- **Les diapositives et vidéos d'Andrew Heiss**
- Chris Walters (2020), *Regression Discontinuity Designs*
- **Carpenter & Dobkin (2009), « The Effect of Alcohol Consumption on Mortality »**

**Lectures complémentaires**

- Imbens & Lemieux (2008)
- Lee & Lemieux (2010)

---

## Séance 12 : Séance de révision

**Contenu**

- Synthèse des notions abordées
- Exercices de révision
- Questions et discussion

# Références

## Ouvrages principaux

- **Angrist, J. D. & Pischke, J.-S. (2015). *Mastering Metrics*.**
- **Introduction to Econometrics with R.**
- **ModernDive.**
- **Wickham, H. & Grolemund, G. *R for Data Science*.**

## Articles de référence

- Angrist, J. D. & Pischke, J.-S. (2010). *The Credibility Revolution in Empirical Economics.*
- Schwabish, J. (2014). *An Economist's Guide to Visualizing Data.*
- Card, D. & Krueger, A. (1994). *Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania.*
- Carpenter, C. & Dobkin, C. (2009). *The Effect of Alcohol Consumption on Mortality: Regression Discontinuity Evidence from the Minimum Drinking Age.*

## Lectures complémentaires

- Cunningham, S. *Causal Inference: The Mixtape.*
- Morgan, S. L. & Winship, C. *Counterfactuals and Causal Inference.*
- Imbens, G. & Lemieux, T. (2008).
- Lee, D. & Lemieux, T. (2010).