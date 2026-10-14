# 🛍️ Shopie - Plateforme E-commerce (Backend & Mobile)

Bienvenue sur le projet **Shopie**, une solution e-commerce complète comprenant une API REST développée avec **Spring Boot** et une application mobile développée avec **React Native (Expo)**.

---

## 📑 Table des matières

1. [Shopie Backend (API REST)](#-shopie-backend---api-rest)
   - [Fonctionnalités](#-fonctionnalités)
   - [Technologies Utilisées](#%EF%B8%8F-technologies-utilisées)
   - [Prérequis](#-prérequis)
   - [Installation & Configuration](#-installation-et-configuration)
   - [Documentation API](#-documentation-api)
2. [Shopie Mobile (React Native)](#-shopie-mobile---application-mobile)
   - [Fonctionnalités](#-fonctionnalités-1)
   - [Technologies Utilisées](#%EF%B8%8F-technologies-utilisées-1)
   - [Installation & Démarrage](#-installation-et-démarrage)
   - [Structure du Projet](#-structure-du-projet)
3. [Comptes de Test](#-comptes-de-test)
4. [Licence](#-licence)

---

# 🚀 Shopie Backend - API REST

Backend REST API pour l'application e-commerce Shopie, développé avec Spring Boot. Cette API est conçue pour être utilisée avec l'application mobile React Native.

## ⚙️ Fonctionnalités

### Authentification & Autorisation
- ✅ Inscription et connexion utilisateur
- ✅ Authentification JWT
- ✅ Gestion des rôles (`USER` / `ADMIN`)
- ✅ Protection des routes sensibles

### Gestion des Produits
- ✅ CRUD complet des produits (Admin)
- ✅ Consultation publique des produits
- ✅ Recherche de produits
- ✅ Gestion du stock

### Panier d'Achat
- ✅ Ajout/suppression d'articles
- ✅ Modification des quantités
- ✅ Vérification du stock en temps réel

### Commandes
- ✅ Création de commandes depuis le panier
- ✅ Suivi des commandes utilisateur
- ✅ Gestion des statuts (`PENDING`, `PAID`, `SHIPPED`, `DELIVERED`)
- ✅ Dashboard admin pour toutes les commandes

### Paiements
- ✅ Création et traitement des paiements
- ✅ Support multi-méthodes (Stripe, PayPal, etc.)
- ✅ Suivi des statuts de paiement
- ✅ Dashboard admin des paiements

## 🛠️ Technologies Utilisées

- Java 21
- Spring Boot 4.0.1
- Spring Security (JWT)
- Spring Data JPA
- MySQL 8.0+
- Maven
- Swagger/OpenAPI 3
- Lombok

## 📋 Prérequis

- Java 21 ou supérieur
- Maven 3.6+
- MySQL 8.0+
- Git

## 🔧 Installation et Configuration

### 1. Cloner le projet
```bash
git clone <repository-url>
cd backend-ecom
