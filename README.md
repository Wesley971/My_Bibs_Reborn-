# 🍼 MyBibs — Suivi de biberons pour jeunes parents

> Né d'une vraie nuit blanche avec ma fille de 1 an.  
> _"On a donné le biberon à quelle heure déjà ?"_ — Cette app répond à cette question.

---

## 📖 L'histoire du projet

Quand on est jeune parent, les nuits se ressemblent toutes : fatigue, biberons à répétition, et cette question lancinante que se posent tous les papas et mamans épuisés — **à quelle heure était le dernier biberon ? Combien de ml ?**

MyBibs est né de ce besoin concret, vécu au quotidien. C'est une application mobile pensée pour les parents qui veulent garder un suivi simple, rapide et efficace des biberons de leur bébé, sans prise de tête.

---

## 📱 Présentation

**MyBibs** est une application mobile développée avec **React Native** et **Expo**, en **TypeScript**. Elle permet de suivre facilement les biberons de bébé : ajout, historique, statistiques et un scanner de codes-barres pour les laits en poudre.

---

## 🎮 Fonctionnalités

- **➕ Ajout de biberon** — Enregistre la quantité en ml, la date/heure et des notes optionnelles
- **📋 Historique** — Consulte tous les biberons enregistrés avec possibilité de suppression
- **📊 Statistiques** — Suivi des tendances de consommation _(en cours de développement)_
- **📷 Scanner** — Scan de codes-barres pour identifier les laits en poudre _(en cours de développement)_
- **💾 Stockage local** — Les données sont sauvegardées en local sur l'appareil via AsyncStorage

---

## 🛠️ Stack technique

| Technologie                            | Usage                            |
| -------------------------------------- | -------------------------------- |
| React Native 0.76                      | Framework mobile cross-platform  |
| Expo 52                                | Toolchain & build                |
| TypeScript 5.3                         | Typage statique                  |
| React Navigation (Stack + Bottom Tabs) | Navigation de l'application      |
| React Native Paper                     | Composants UI Material Design    |
| AsyncStorage                           | Persistance des données en local |
| Expo Camera                            | Scan de codes-barres             |

---

## 🚀 Installation & lancement

### Prérequis

- Node.js >= 18
- npm ou yarn
- Application **Expo Go** sur votre téléphone (iOS ou Android)

### Installation

```bash
# Cloner le dépôt
git clone https://github.com/Wesley971/MyBibs.git
cd MyBibs

# Installer les dépendances
npm install

# Lancer l'application
npm start
```

Scannez ensuite le QR code avec l'application **Expo Go** sur votre téléphone.

---

## 📁 Structure du projet

```
MyBibs/
├── App.tsx                        # Point d'entrée principal
├── src/
│   ├── components/
│   │   └── ScreenWrapper.tsx      # Composant wrapper réutilisable
│   ├── navigation/
│   │   └── AppNavigator.tsx       # Navigation Stack + Bottom Tabs
│   ├── screens/
│   │   ├── AddBottleScreen.tsx    # Ajout d'un biberon
│   │   ├── HistoryScreen.tsx      # Historique des biberons
│   │   ├── StatsScreen.tsx        # Statistiques
│   │   └── ScanScreen.tsx         # Scanner de codes-barres
│   └── storage/
│       └── bottleStorage.ts       # Couche de persistance AsyncStorage
├── assets/                        # Icônes et images
└── app.json                       # Configuration Expo
```

---

## 🗺️ Roadmap

- [x] Ajout de biberon avec quantité, date et notes
- [x] Historique avec suppression et confirmation
- [x] Navigation par onglets (Bottom Tabs)
- [x] Scanner de codes-barres (base)
- [ ] Statistiques complètes (quantité journalière, moyenne, graphiques)
- [ ] Mode multijoueur familial — papa et maman partagent le même suivi
- [ ] Notifications de rappel
- [ ] Personnage virtuel type Tamagotchi 🐣 — le bébé évolue selon les données réelles
- [ ] Système de récompenses et badges pour les parents

---

## 🎯 Objectif pédagogique

Ce projet m'a permis de progresser concrètement sur :

- **React Native & Expo** — développement mobile cross-platform
- **TypeScript** — typage fort, interfaces et navigation typée
- **React Navigation** — architecture Stack + Bottom Tabs combinés
- **AsyncStorage** — persistance des données côté client
- **Architecture en couches** — séparation screens / navigation / storage / components
- **React Native Paper** — intégration d'une librairie UI complète

---

## 👨‍💻 À propos

Projet développé par **Wesley**.
Ancien contrôleur SNCF, aujourd'hui passionné de code et de jeux vidéo, je construis ce projet avec une motivation toute personnelle : ma fille. 🍼

[![GitHub](https://img.shields.io/badge/GitHub-Wesley971-black?logo=github)](https://github.com/Wesley971)

---

> _"Le meilleur projet est celui qu'on construit pour une vraie raison."_
