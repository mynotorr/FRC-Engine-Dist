# 🚀 FRC Engine - Windows Gaming Optimization Suite

<p align="center">
  <img src="https://img.shields.io/github/v/release/mynotorr/FRC-Engine-Dist?style=for-the-badge&color=cyan">
  <img src="https://img.shields.io/github/downloads/mynotorr/FRC-Engine-Dist/total?style=for-the-badge&color=green">
  <img src="https://img.shields.io/badge/Language-PowerShell-blue?style=for-the-badge&logo=powershell">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows">
</p>

---

## 🎯 Qu’est-ce que FRC Engine ?

**FRC Engine** est une suite d’optimisation Windows orientée **gaming compétitif** et **faible latence**.

Son objectif n’est pas de “faire apparaître des FPS par magie”, mais d’améliorer ce qui compte vraiment en jeu :

- la **réactivité**
- la **stabilité des frametimes**
- la **propreté mémoire**
- la **gestion du focus jeu**
- la **réduction des perturbations en arrière-plan**
- la **cohérence système pendant une session gaming**

FRC Engine combine :
- optimisation système
- maintenance temps réel
- nettoyage mémoire
- détection active du jeu
- overlay live
- profils dynamiques orientés performance

- 🧠 **Important :**  
- **Low Latency**, **Game Focus** et **FPS Boost** peuvent être utilisés **sans lancer les optimisations système**.
- 👉 Donc si vous ne souhaitez pas modifier Windows en profondeur, vous pouvez simplement utiliser les **modules live** pendant vos sessions de jeu.
- Les optimisations système permettent d’aller plus loin, mais les fonctions live restent déjà **utiles, actives et indépendantes** à elles seules. 🎮⚡

---

## 👀 Aperçu de l’interface

<p align="center">
  <img src="https://raw.githubusercontent.com/mynotorr/FRC-Engine-Dist/main/preview.png" alt="FRC Engine Interface Preview" width="800">
</p>

---

## 🖥️ Aperçu de l’overlay en jeu

<p align="center">
  <img src="https://raw.githubusercontent.com/mynotorr/FRC-Engine-Dist/main/overlay.png" alt="FRC Engine Overlay Preview" width="500">
</p>
<p align="center"><em>Un overlay discret, lisible et pensé pour le jeu.</em></p>

---

# ✨ Ce que fait FRC Engine

## ⚡ 1) Optimisation principale du système

FRC Engine peut appliquer une base d’optimisation Windows pensée pour le jeu afin de repartir sur une configuration plus propre et plus cohérente.

Cela peut inclure selon la version du moteur :
- ajustements système orientés performance
- réduction de certaines frictions inutiles côté Windows
- nettoyage de paramètres peu utiles en session gaming
- consolidation d’un environnement plus stable pour le jeu

> Certaines optimisations peuvent nécessiter un **redémarrage** pour être pleinement prises en compte.

---

## 🧠 2) Maintenance temps réel pendant le jeu

L’un des points forts du logiciel est sa logique **live**.

Quand FRC Engine reste ouvert pendant la session :
- il surveille le contexte système
- il détecte le jeu au premier plan
- il adapte son comportement automatiquement
- il maintient certaines optimisations pendant la partie

Ce fonctionnement permet un comportement plus propre qu’un simple “one-shot”.

---

## 🎮 3) Détection active du jeu

FRC Engine ne se contente pas de regarder un bouton activé ou désactivé.

Le moteur utilise une **détection active du jeu** basée notamment sur :
- le processus au premier plan
- la fenêtre active
- le contexte réel bureau / jeu
- la qualité de confirmation du focus
- la reprise après **Alt+Tab**
- des heuristiques internes pour mieux reconnaître les jeux compatibles

Le moteur ne traite donc pas tous les cas de la même manière :
- il sait faire la différence entre un vrai contexte jeu
- un retour bureau
- une transition
- une reprise après Alt+Tab
- un état encore incertain

---

## 🕹️ 4) Game Focus

**Game Focus** est le moteur qui renforce le comportement orienté jeu quand un titre compatible est détecté.

Concrètement, il sert à :
- mieux accrocher le jeu actif
- maintenir la priorité du bon processus
- améliorer la cohérence de focus
- éviter certains faux états après retour bureau
- mieux gérer les transitions **jeu ↔ bureau**
- rendre la reprise après **Alt+Tab** plus fiable

Le moteur Game Focus a été pensé pour :
- mieux se réveiller au retour en jeu
- éviter les faux maintiens
- éviter les états incohérents
- garder un comportement plus stable sur les jeux compétitifs

---

## ⚡ 5) Low Latency

**Low Latency** pousse la logique du moteur vers une réponse plus agressive et plus nerveuse.

Son rôle est d’aider à :
- réduire la sensation de lourdeur
- améliorer la réactivité générale
- réduire certaines latences parasites
- rendre le comportement du système plus “tendu” pour le jeu

Ce module tient compte du contexte et ne se contente pas d’un état fixe :
- en jeu, il peut monter en puissance
- hors jeu, il retombe proprement en veille
- son affichage a été harmonisé pour mieux refléter l’état réel

---

## 🚀 6) FPS Boost

**FPS Boost** ne promet pas des gains irréalistes, mais il applique de vraies actions sur le contexte de jeu.

Quand il est actif, le moteur peut :
- renforcer la priorité du jeu
- améliorer le maintien du processus principal
- réappliquer plus vite le boost si nécessaire
- augmenter la pression sur l’arrière-plan
- maintenir un contexte plus favorable aux frametimes
- assister la fluidité perçue et la stabilité en partie

Le but réel du module est surtout :
- moins de pollution en fond
- meilleure stabilité
- frametimes plus propres
- moins de micro-stutters
- parfois quelques FPS en plus selon le jeu et la machine

---

## 🧹 7) Auto-Clean & nettoyage mémoire

FRC Engine intègre une logique de nettoyage mémoire pour limiter l’accumulation inutile pendant les sessions.

Cela permet de :
- garder un état mémoire plus propre
- éviter certaines dérives après plusieurs minutes/heures de session
- réduire certains comportements parasites
- accompagner les modules live pendant le jeu

Le moteur peut agir :
- automatiquement via **AUTO-CLEAN**
- manuellement via **VIDER RAM**
- plus profondément via **DEEP CLEAN**

---

## 🌐 8) Nettoyage réseau

Le module **NETTOYAGE RÉSEAU** sert à remettre à plat certaines bases réseau pour repartir sur un environnement plus sain.

Il peut être utile :
- après des changements système
- après des soucis réseau
- après des tests multiples
- pour repartir sur une base propre

---

## 📊 9) Overlay live

L’overlay permet de visualiser en direct l’état du moteur sans quitter le jeu.

Il affiche notamment :
- les états **Low Latency**
- les états **Game Focus**
- le niveau de poussée réel du moteur
- des indicateurs de fluidité et de santé système selon la version

Les états ont été harmonisés pour être plus lisibles :

- **ARRÊT** → module désactivé
- **VEILLE** → module actif mais pas engagé en jeu
- **MIN** → engagement léger
- **MOYEN** → engagement intermédiaire
- **MAX** → engagement fort

---

## 🤖 10) Adaptation automatique selon le jeu

Le moteur ne repose plus uniquement sur des seuils figés.

FRC Engine peut désormais :
- adapter ses seuils selon le jeu détecté
- se montrer plus souple sur certains profils
- être plus prudent en phase de transition
- adapter la lecture de puissance selon la qualité de détection
- mieux gérer la différence entre bureau, reprise et vraie session de jeu

L’objectif est simple :
**avoir un moteur plus intelligent, plus automatique, et moins dépendant de réglages manuels.**

---

# 🕹️ Guide des fonctions

## ⚡ Optimisation principale
- **LANCER OPTI** : applique les optimisations principales prévues par FRC Engine
- **ROLLBACK** : tente de revenir à un état plus proche de la configuration par défaut

## 🧠 Moteurs temps réel
- **AUTO-CLEAN** : nettoyage mémoire automatique pendant la session
- **GAME FOCUS** : renforce la focalisation sur le jeu actif détecté
- **LOW LATENCY** : comportement plus agressif orienté réactivité
- **FPS BOOST** : pousse davantage le contexte de performance autour du jeu
- **VIDER RAM** : purge mémoire manuelle immédiate

## 🧹 Nettoyage
- **DEEP CLEAN** : nettoyage plus poussé
- **NETTOYAGE RÉSEAU** : remise à plat réseau

## 🖥️ Monitoring
- **OVERLAY** : affichage live en jeu
- **INFO LOGICIEL / SYSTÈME** : informations sur le moteur, le système et le matériel

## 🔌 Démarrage
- **DÉMARRAGE AUTOMATIQUE** : lancement automatique à l’ouverture de session

---

# 📈 Ce que FRC Engine cherche à améliorer concrètement

Selon le jeu, la machine et le contexte, FRC Engine peut aider à améliorer :

- la **réactivité générale**
- la **sensation de fluidité**
- la **stabilité des frametimes**
- la **propreté mémoire**
- la **tenue de session**
- la **gestion du focus jeu**
- les transitions **jeu / bureau**
- la **reprise après Alt+Tab**
- la **cohérence de l’environnement Windows** pendant le jeu

---

# ⚠️ Important

## Utilisation de l’optimisation principale
Le bouton **LANCER OPTI** n’a pas vocation à être spam tous les jours inutilement.

Il est surtout recommandé :
- après installation
- après une grosse mise à jour Windows
- après un gros changement système
- ponctuellement pour repartir sur une base propre

## Redémarrage
Certaines optimisations système peuvent demander un **redémarrage**.

## Utilisation en session
Pour profiter pleinement des modules live :
**il est recommandé de laisser FRC Engine ouvert pendant que vous jouez.**

---

# ✅ Ce que la version actuelle apporte

- meilleure cohérence globale du moteur
- meilleure détection active du jeu
- meilleure gestion de **Game Focus**
- comportement **Low Latency** plus propre
- reprise **Alt+Tab** renforcée
- overlay plus cohérent
- états plus lisibles
- moteur plus intelligent et plus automatique
- meilleure synergie entre les modules live
- base plus propre et plus stable

---

# 🛡️ Sécurité & philosophie

- **Zéro bloatware**
- **Approche orientée performance**
- **Utilisation des ressources natives de Windows**
- **Logique pensée pour le gaming compétitif**
- **Base consolidée pour une utilisation plus stable**

---

# ❤️ Crédits

**Powered by Mynotorr and Bobby**

**Développé par [Mynotorr](https://github.com/mynotorr)**

---

# 🔗 Liens

<p align="left">
  <a href="https://github.com/mynotorr/FRC-Engine-Dist/releases">
    <img src="https://img.shields.io/badge/TÉLÉCHARGER-FRC_ENGINE-cyan?style=for-the-badge&logo=github">
  </a>
  <a href="https://www.paypal.com/ncp/payment/H52TKW7E6PV2S">
    <img src="https://img.shields.io/badge/SOUTENIR-PAYPAL-blue?style=for-the-badge&logo=paypal">
  </a>
  <a href="https://discord.gg/votre_lien">
    <img src="https://img.shields.io/badge/DISCORD-COMMUNAUTÉ-5865F2?style=for-the-badge&logo=discord&logoColor=white">
  </a>
</p>
