# 📚 Bibliothèque Universitaire - Gestion des emprunts

![Version](https://img.shields.io/badge/version-2.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Application web interactive pour la gestion d'une bibliothèque universitaire, développée dans le cadre du Mini-Projet de Structures de Données Avancées (L2IT).

## 🎯 Objectifs pédagogiques

- Implémentation d'un **Arbre Binaire de Recherche (ABR)** pour la gestion des livres
- Utilisation de **listes chaînées** pour la gestion des emprunts
- Manipulation des structures de données linéaires et arborescentes
- Gestion de la persistance des données (LocalStorage / fichiers JSON)

## ✨ Fonctionnalités

### Partie 1 - Gestion des livres (ABR)
- ✅ Ajout de livres avec insertion dans l'ABR (tri par numéro)
- ✅ Affichage du catalogue (parcours infixe)
- ✅ Recherche par numéro ou par titre
- ✅ Vérification de disponibilité des exemplaires
- ✅ Tri alphabétique par titre ou auteur
- ✅ Visualisation graphique de l'arbre

### Partie 2 - Gestion des emprunts (Liste chaînée)
- ✅ Emprunt de livres avec contrôle des exemplaires
- ✅ Liste complète des emprunts
- ✅ Retour de livres avec mise à jour des disponibilités
- ✅ Filtrage (en cours, en retard, tous)

### Partie 3 - Rapports et recherches
- ✅ Consultation des emprunts par étudiant
- ✅ Détection des retards par rapport à une date donnée
- ✅ Statistiques en temps réel

### Fonctionnalités supplémentaires
- 💾 Sauvegarde automatique dans le navigateur
- 📤 Export / Import au format JSON
- 🖨 Génération de rapports PDF imprimables
- 📱 Interface responsive (mobile/tablette/desktop)

## 🛠 Technologies utilisées

- HTML5 / CSS3
- JavaScript (Vanilla, sans framework)
- LocalStorage API
- Canvas pour la visualisation de l'arbre

## 🚀 Démo en ligne

[Accéder à l'application](https://TON-PSEUDO.github.io/bibliotheque/)

## 📦 Installation locale

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/TON-PSEUDO/bibliotheque.git
