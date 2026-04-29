# 🚀 FRC Engine 2.1 - Windows Gaming Optimization Suite

<p align="center">
  <a href="https://github.com/mynotorr/FRC-Engine-Dist/releases">
    <img src="https://img.shields.io/github/v/release/mynotorr/FRC-Engine-Dist?style=for-the-badge&color=cyan" alt="Release">
  </a>
  <a href="https://github.com/mynotorr/FRC-Engine-Dist/releases">
    <img src="https://img.shields.io/github/downloads/mynotorr/FRC-Engine-Dist/total?style=for-the-badge&color=green" alt="Downloads">
  </a>
  <a href="https://github.com/mynotorr/FRC-Engine-Dist">
    <img src="https://img.shields.io/badge/Language-PowerShell-blue?style=for-the-badge&logo=powershell" alt="PowerShell">
  </a>
  <a href="https://github.com/mynotorr/FRC-Engine-Dist/releases">
    <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows" alt="Windows">
  </a>
</p>

<p align="center">
  <a href="https://github.com/mynotorr/FRC-Engine-Dist/releases">
    <img src="https://img.shields.io/badge/TÉLÉCHARGER-FRC_ENGINE-cyan?style=for-the-badge&logo=github" alt="Télécharger FRC Engine">
  </a>
</p>

---

## 🎯 Qu’est-ce que FRC Engine ?

**FRC Engine** est une suite d’optimisation Windows pensée pour le **gaming compétitif**, la **faible latence** et la **stabilité en session de jeu**.

Son objectif n’est pas de promettre des FPS irréalistes, mais d’améliorer ce qui compte réellement pendant une session gaming :

- la **réactivité**
- la **stabilité des frametimes**
- la **propreté mémoire**
- la **réduction des tâches parasites**
- la **priorité du jeu actif**
- la **cohérence Windows pendant le jeu**
- la **gestion du focus application / jeu**
- la **fluidité ressentie**

FRC Engine combine plusieurs modules :

- optimisation Windows
- maintenance temps réel
- nettoyage mémoire
- détection active du jeu
- gestion du focus application
- overlay live
- profils dynamiques orientés performance
- mode boost global simplifié avec **ALL IN ONE BOOST**

---

## 🧠 Important

Les modules live de FRC Engine peuvent être utilisés **sans lancer l’optimisation Windows complète**.

Vous pouvez donc utiliser directement :

- **APP FOCUS**
- **GAME FOCUS**
- **LOW LATENCY**
- **FPS BOOST**
- **ALL IN ONE BOOST**
- **AUTO-CLEAN**
- **OVERLAY**

sans forcément modifier Windows en profondeur.

L’optimisation Windows principale permet d’aller plus loin, mais les modules live restent déjà utiles et indépendants pendant vos sessions de jeu.

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

# ✨ Nouveautés principales de la version 2.1

La version **2.1** apporte une grosse évolution du moteur par rapport à la 2.0.

Elle améliore notamment :

- la logique du bouton **Optimisation Windows**
- l’ajout du bouton **APP FOCUS**
- l’ajout du mode **ALL IN ONE BOOST**
- la cohérence entre les modules live
- la lisibilité des états
- le comportement après optimisation système
- la gestion du redémarrage
- la stabilité générale du moteur pendant les sessions gaming

---

## 🪟 1) Optimisation Windows améliorée

Le bouton **Optimisation Windows** applique une base d’optimisation système pensée pour le jeu.

Son rôle est de préparer Windows pour un comportement plus propre et plus cohérent en session gaming.

L’optimisation peut inclure selon la version du moteur :

- ajustements système orientés performance
- réduction de certaines frictions Windows inutiles
- nettoyage de paramètres peu utiles en jeu
- amélioration de la cohérence système
- préparation d’un environnement plus stable pour les modules live
- optimisation de certains comportements en arrière-plan

Après l’optimisation, le bouton peut afficher **REDÉMARRER** afin d’indiquer qu’un redémarrage est recommandé pour finaliser certaines modifications.

Après redémarrage du PC, le bouton revient à son état normal :

**optimisation windows**

Cette logique permet de garder une interface claire, sans blocage inutile ni timer forcé.

---

## 🔁 2) Résumé du comportement Optimisation Windows

Le fonctionnement est simple :

1. Vous cliquez sur **optimisation windows**
2. FRC Engine applique les optimisations prévues
3. Le bouton affiche **REDÉMARRER**
4. Vous redémarrez le PC
5. Au prochain lancement, le bouton revient automatiquement à **optimisation windows**

Il n’y a plus de timer d’attente inutile après redémarrage.

---

## 🎯 3) APP FOCUS

La version 2.1 introduit le bouton **APP FOCUS**.

**APP FOCUS** est pensé pour renforcer la priorité et la cohérence de l’application active.

Son objectif est d’aider Windows à mieux se concentrer sur ce qui est réellement utilisé au premier plan.

Il peut être utile pour :

- améliorer la réactivité de l’application active
- limiter certaines perturbations en arrière-plan
- renforcer la cohérence du focus Windows
- mieux accompagner les jeux et applications importantes
- améliorer la sensation de stabilité pendant l’utilisation

APP FOCUS fonctionne comme une couche complémentaire aux modules gaming.

Il ne remplace pas **GAME FOCUS**, mais il vient renforcer la logique globale du moteur.

---

## 🕹️ 4) GAME FOCUS

**GAME FOCUS** reste le moteur spécialisé dans la détection et le maintien du jeu actif.

Il aide à :

- mieux accrocher le jeu détecté
- maintenir la priorité du bon processus
- améliorer la cohérence entre bureau et jeu
- réduire les faux états après Alt+Tab
- améliorer la reprise au retour en jeu
- renforcer la stabilité du contexte gaming

Le moteur Game Focus a été pensé pour éviter :

- les faux maintiens
- les pertes de focus inutiles
- les états incohérents
- les transitions mal interprétées entre jeu et bureau

---

## ⚡ 5) LOW LATENCY

**LOW LATENCY** pousse la logique du moteur vers une réponse plus nerveuse et plus réactive.

Son rôle est d’aider à :

- réduire la sensation de lourdeur
- améliorer la réactivité générale
- limiter certaines latences parasites
- rendre le comportement système plus tendu pour le jeu

Le module tient compte du contexte :

- en jeu, il peut monter en puissance
- hors jeu, il peut rester en veille
- pendant les transitions, il évite les comportements trop agressifs

---

## 🚀 6) FPS BOOST

**FPS BOOST** applique des actions orientées performance autour du jeu actif.

Son objectif n’est pas de promettre des gains irréalistes, mais d’aider à maintenir un contexte plus favorable au jeu.

Quand il est actif, le moteur peut :

- renforcer la priorité du jeu
- maintenir le processus principal dans un état plus favorable
- réduire certaines pressions de l’arrière-plan
- améliorer la stabilité des frametimes
- assister la fluidité ressentie
- limiter certains micro-stutters selon les configurations

Le gain réel dépend du jeu, de la machine, de Windows et du contexte d’utilisation.

---

## 🔥 7) ALL IN ONE BOOST

La version 2.1 introduit **ALL IN ONE BOOST**.

Ce bouton permet de simplifier l’utilisation du moteur en regroupant les principales fonctions live orientées performance.

L’objectif est simple :

**activer rapidement un mode gaming complet sans devoir gérer chaque module un par un.**

ALL IN ONE BOOST peut regrouper ou piloter plusieurs logiques selon le moteur :

- APP FOCUS
- GAME FOCUS
- LOW LATENCY
- FPS BOOST
- logique de maintien actif
- adaptation selon le contexte jeu / bureau
- synergie des modules live

Ce mode est pensé pour les utilisateurs qui veulent une utilisation plus simple :

1. ouvrir FRC Engine
2. activer ALL IN ONE BOOST
3. lancer le jeu
4. laisser le moteur gérer le comportement live

ALL IN ONE BOOST rend FRC Engine plus accessible, tout en gardant la logique avancée du moteur.

---

## 🧹 8) AUTO-CLEAN & nettoyage mémoire

FRC Engine intègre une logique de nettoyage mémoire pour limiter l’accumulation inutile pendant les sessions.

Cela permet de :

- garder un état mémoire plus propre
- réduire certaines dérives après plusieurs minutes ou heures de jeu
- accompagner les modules live
- limiter certains comportements parasites
- conserver une session plus stable

Le moteur peut agir de plusieurs façons :

- automatiquement via **AUTO-CLEAN**
- manuellement via **VIDER RAM**
- plus profondément via **DEEP CLEAN**

---

## 🌐 9) Nettoyage réseau

Le module **NETTOYAGE RÉSEAU** permet de remettre à plat certaines bases réseau.

Il peut être utile :

- après des soucis réseau
- après des tests multiples
- après une mise à jour Windows
- après des changements de configuration
- pour repartir sur une base réseau plus propre

Ce module ne remplace pas une bonne connexion internet, mais il peut aider à nettoyer certains états réseau côté Windows.

---

## 📊 10) Overlay live

L’overlay permet de visualiser l’état du moteur en direct pendant une session.

Il peut afficher selon la version :

- l’état de Low Latency
- l’état de Game Focus
- l’état du moteur live
- le niveau de poussée appliqué
- des informations de santé système
- des indicateurs de fluidité et de stabilité

Les états sont pensés pour être simples à comprendre :

- **ARRÊT** → module désactivé
- **VEILLE** → module actif mais pas engagé
- **MIN** → engagement léger
- **MOYEN** → engagement intermédiaire
- **MAX** → engagement fort

---

## 🤖 11) Adaptation automatique selon le contexte

FRC Engine ne repose pas uniquement sur des boutons fixes.

Le moteur analyse le contexte afin d’adapter son comportement :

- jeu détecté
- application active
- retour bureau
- reprise après Alt+Tab
- transition entre fenêtres
- état du moteur
- cohérence du focus
- qualité de détection

L’objectif est d’avoir un moteur plus intelligent, plus automatique et plus stable pendant les sessions gaming.

---

# 🕹️ Guide des fonctions

## 🪟 Optimisation principale

- **optimisation windows** : applique les optimisations principales prévues par FRC Engine
- **REDÉMARRER** : indique qu’un redémarrage est recommandé après optimisation
- **ROLLBACK** : tente de revenir à un état plus proche de la configuration par défaut

---

## 🔥 Boost & performance live

- **ALL IN ONE BOOST** : active une logique globale de boost gaming simplifiée
- **APP FOCUS** : renforce le focus et la priorité de l’application active
- **GAME FOCUS** : renforce le comportement orienté jeu quand un jeu est détecté
- **LOW LATENCY** : applique une logique orientée réactivité et faible latence
- **FPS BOOST** : pousse le contexte de performance autour du jeu actif

---

## 🧠 Maintenance temps réel

- **AUTO-CLEAN** : nettoyage mémoire automatique pendant la session
- **VIDER RAM** : purge mémoire manuelle immédiate
- **DEEP CLEAN** : nettoyage plus poussé

---

## 🌐 Nettoyage

- **NETTOYAGE RÉSEAU** : remise à plat de certaines bases réseau Windows

---

## 🖥️ Monitoring

- **OVERLAY** : affichage live en jeu
- **INFO LOGICIEL / SYSTÈME** : informations sur le moteur, le système et le matériel

---

## 🔌 Démarrage

- **DÉMARRAGE AUTOMATIQUE** : lancement automatique de FRC Engine à l’ouverture de session Windows

---

# 📈 Ce que FRC Engine cherche à améliorer

Selon le jeu, la machine et le contexte, FRC Engine peut aider à améliorer :

- la réactivité générale
- la sensation de fluidité
- la stabilité des frametimes
- la propreté mémoire
- la tenue de session
- la gestion du focus jeu
- la gestion du focus application
- les transitions jeu / bureau
- la reprise après Alt+Tab
- la cohérence Windows pendant le jeu
- la réduction des perturbations en arrière-plan

---

# ✅ Ce que la version 2.1 apporte

La version **2.1** apporte une base plus complète et plus propre que la 2.0.

Principales améliorations :

- ajout du bouton **APP FOCUS**
- ajout du mode **ALL IN ONE BOOST**
- amélioration du comportement **Optimisation Windows**
- affichage **REDÉMARRER** après optimisation
- retour automatique à **optimisation windows** après redémarrage
- suppression du timer d’attente inutile
- meilleure cohérence entre les modules live
- meilleure lisibilité des états
- logique plus simple pour l’utilisateur
- moteur plus propre pour les sessions gaming
- meilleure synergie entre APP FOCUS, GAME FOCUS, LOW LATENCY et FPS BOOST

---

# ⚠️ Important

## Optimisation Windows

Le bouton **optimisation windows** n’a pas vocation à être utilisé tous les jours inutilement.

Il est surtout recommandé :

- après installation
- après une grosse mise à jour Windows
- après un changement important de configuration
- après un problème système
- ponctuellement pour repartir sur une base propre

---

## Redémarrage

Certaines optimisations peuvent nécessiter un redémarrage pour être pleinement prises en compte.

Après optimisation, si le bouton affiche **REDÉMARRER**, il est recommandé de redémarrer le PC.

Après redémarrage, FRC Engine revient automatiquement à son état normal.

---

## Utilisation en session

Pour profiter pleinement des modules live, il est recommandé de laisser FRC Engine ouvert pendant que vous jouez.

Les modules comme **APP FOCUS**, **GAME FOCUS**, **LOW LATENCY**, **FPS BOOST** et **ALL IN ONE BOOST** sont pensés pour fonctionner pendant la session.

---

# 🛡️ Sécurité & philosophie

FRC Engine repose sur une approche simple :

- **zéro bloatware**
- **pas de promesse magique**
- **approche orientée performance réelle**
- **utilisation des ressources natives de Windows**
- **logique pensée pour le gaming compétitif**
- **interface simple**
- **moteur live plus intelligent**
- **base consolidée pour une utilisation plus stable**

---

# ❤️ Crédits

**Powered by Mynotorr and Bobby**

**Développé par [Mynotorr](https://github.com/mynotorr)**

---

# 🔗 Liens

<p align="left">
  <a href="https://github.com/mynotorr/FRC-Engine-Dist/releases">
    <img src="https://img.shields.io/badge/TÉLÉCHARGER-FRC_ENGINE-cyan?style=for-the-badge&logo=github" alt="Télécharger FRC Engine">
  </a>
  <a href="https://www.paypal.com/ncp/payment/H52TKW7E6PV2S">
    <img src="https://img.shields.io/badge/SOUTENIR-PAYPAL-blue?style=for-the-badge&logo=paypal" alt="Soutenir via PayPal">
  </a>
  <a href="https://discord.gg/votre_lien">
    <img src="https://img.shields.io/badge/DISCORD-COMMUNAUTÉ-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord Communauté">
  </a>
</p>
