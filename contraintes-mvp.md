# ⚠️ Contraintes du MVP (Minimum Viable Product)

Ce document définit les limites et contraintes du produit minimum viable (MVP) afin de focaliser les efforts sur la valeur essentielle.

## 🎯 Périmètre du MVP (Scope)

### ✅ Ce qui EST dans le MVP (Inclus)
*   **Fonctionnalité 1** : Création d'alerte ou de demande d'aide simplifiée.
*   **Fonctionnalité 2** : Visualisation des alertes actives à proximité.
*   **Fonctionnalité 3** : Prise en charge d'une alerte par un aidant.

### ❌ Ce qui n'est PAS dans le MVP (Hors scope)
*   Système de notation ou de réputation complexe.
*   Paiements ou transactions financières intégrées (reporté à la v2).
*   Application mobile native (utilisation d'un site web Responsive/PWA).

## ⚙️ Contraintes Techniques & d'Architecture
*   **Langages & Frameworks** : Utilisation d'une stack légère et éprouvée pour accélérer le développement.
*   **Données** : Base de données relationnelle simple, conforme au stockage minimal des données sensibles.
*   **Hébergement** : Plateforme cloud gratuite ou à faible coût (ex: Render, Supabase) pour la phase de test.

## 📅 Contraintes de Temps & de Ressources
*   **Jalon Critique** : Le MVP doit être fonctionnel pour les tests utilisateurs d'ici la date du jalon A3.
*   **Effectifs** : Développement assuré par l'équipe actuelle à hauteur de son temps disponible hebdomadaire.

## ⚖️ Sécurité & Réglementation
*   **RGPD** : Collecter uniquement le strict nécessaire (Nom, Prénom, Numéro de téléphone optionnel).
*   **Consentement** : L'utilisateur doit accepter explicitement le partage de sa géolocalisation.
