# Création d'une application web à trois couches avec Spring.NET et VB.NET

➡️ Cours associé :  
[Création d'une application web à trois couches avec Spring.NET et VB.NET](https://stahe.github.io/web3tier-dotnet-avril-2005/)

---

## Présentation

Ce document explique comment développer une **application web à architecture trois couches** en utilisant **VB.NET**, **ASP.NET** et **Spring.NET**.  

L'objectif est de montrer comment structurer une application en séparant clairement :

- l'interface utilisateur  
- la logique métier  
- l'accès aux données  

Le framework **Spring.NET** est utilisé pour configurer et assembler les composants de l'application à l'aide du principe **IoC (Inversion of Control)**.

Cette approche permet notamment de modifier l’implémentation d’une couche sans impacter les autres parties de l’application. 

---

## Objectifs du tutoriel

Les principaux objectifs de ce document sont :

- écrire une **application web à 3 couches** :
  - interface utilisateur
  - couche métier
  - couche d’accès aux données
- configurer l’application avec **Spring IoC**
- produire **plusieurs versions de l’application** en changeant l’implémentation d’une ou plusieurs couches afin d’illustrer la flexibilité de l’architecture. 

---

## Outils utilisés

Le tutoriel s’appuie sur les outils suivants :

- **Visual Studio .NET** — environnement de développement
- **Cassini** — serveur web pour l’exécution de l’application
- **NUnit** — framework de tests unitaires
- **Spring.NET** — configuration et intégration des différentes couches de l’application web 

---

## Niveau du document

Ce document s’adresse à un public **intermédiaire à avancé**. Sa compréhension suppose la maîtrise préalable de plusieurs concepts liés au développement .NET et web. 

---

## Prérequis recommandés

Pour suivre ce tutoriel dans de bonnes conditions, il est recommandé de connaître :

- le **langage VB.NET**
- le **développement web avec ASP.NET**
- le principe **IoC (Inversion of Control)**
- les bases du framework **Spring.NET** 

---

## Documents conseillés

Les documents suivants peuvent être utiles pour acquérir les prérequis :

- *Introduction au langage VB.NET par l'exemple*
- *Développement WEB avec ASP.NET 1.1*
- *Spring IoC pour .NET*
- Documentation officielle **Spring.NET** 

---

## Contexte et approche pédagogique

Ce tutoriel s'inspire d’un document équivalent réalisé dans l’écosystème Java :

**Architectures à 3 couches et architectures MVC avec Struts, Spring et Java**

L’objectif est de montrer que :

- les architectures **Java (J2EE)** et **.NET** reposent sur des principes très similaires
- les compétences acquises dans un environnement peuvent être **réutilisées dans l’autre**. 

---

## Architecture présentée

L’application développée suit une architecture **MVC à trois couches** :
