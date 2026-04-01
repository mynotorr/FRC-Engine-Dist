# 🚀 FRC Engine v1.0.6 - Optimization Suite

<p align="center">
  <img src="https://img.shields.io/github/v/release/mynotorr/FRC-Engine-Dist?style=for-the-badge&color=cyan">
  <img src="https://img.shields.io/github/downloads/mynotorr/FRC-Engine-Dist/total?style=for-the-badge&color=green">
  <img src="https://img.shields.io/badge/Language-PowerShell-blue?style=for-the-badge&logo=powershell">
</p>

---

## 👀 Preview
<p align="center">
  <img src="https://raw.githubusercontent.com/mynotorr/FRC-Engine-Dist/main/preview.png" alt="FRC Engine Preview" width="800">
</p>

---

**FRC Engine** est une suite d'optimisation de "bas niveau" conçue pour transformer Windows en une plateforme de jeu ultra-réactive. Contrairement aux simples nettoyeurs de fichiers, FRC Engine agit directement sur le **Kernel (noyau)** pour réduire l'**Input Lag** et stabiliser les **Frametimes**.

---

## ⚠️ AVERTISSEMENTS IMPORTANTS

### 🕒 Fréquence d'utilisation
L'optimisation système (bouton **LANCER OPTI**) ne doit être effectuée qu'**UNE FOIS PAR MOIS** au maximum, ou après une mise à jour majeure de Windows. Une fois les paramètres injectés dans le Kernel, ils sont persistants. Il est inutile et déconseillé de relancer l'optimisation tous les jours.

### 📉 Saccades temporaires (Shaders)
Après avoir utilisé FRC Engine, il est **NORMAL** de ressentir des micro-saccades lors de vos premières minutes de jeu. 
* **Pourquoi ?** Le script nettoie les "Shaders Caches" pour garantir une base saine. 
* **Solution :** Jouez normalement pendant 5 à 10 minutes. Votre carte graphique va reconstruire des fichiers de cache propres, et la fluidité sera bien supérieure à celle d'origine.

---

## 🛠️ Pourquoi laisser FRC allumé ? (Maintenance Live)
Pour une efficacité maximale, **FRC ENGINE DOIT RESTER OUVERT PENDANT QUE VOUS JOUEZ** :
* **AUTO-CLEAN :** Sans lui, Windows accumule des "déchets" en RAM qui causent des micro-saccades (*stutters*) lors de vos mouvements de souris rapides. Il nettoie votre mémoire toutes les 6 secondes.
* **GAME FOCUS :** Si FRC est fermé, Windows reprend ses mauvaises habitudes et traite les tâches de fond avant votre jeu. Game Focus force votre CPU à se concentrer uniquement sur votre performance.

---

## 🕹️ Guide Complet des Boutons & Fonctions

### ⚡ Optimisation Principale
* **LANCER OPTI :** Le bouton maître. Il applique les 38 optimisations Kernel (Win32Priority, HPET, IRQ). **Nécessite un redémarrage.**
* **ROLLBACK :** **BOUTON DE SECOURS.** Restaure instantanément les valeurs par défaut de Windows.

### 🧠 Maintenance Temps Réel
* **AUTO-CLEAN :** Active le nettoyage intelligent de la RAM toutes les 6 secondes.
* **GAME FOCUS :** Alloue dynamiquement une priorité CPU maximale à votre jeu actif.
* **VIDER RAM :** Purge manuelle instantanée de la mémoire vive.

### 🧹 Nettoyage & Réseau
* **DEEP CLEAN :** Supprime les fichiers temporaires et les résidus massifs de Windows Update.
* **NETTOYAGE RÉSEAU :** Reset TCP/IP, vide le cache DNS et stabilise le ping.
* **SHADER CACHE :** Purge les caches NVIDIA/AMD pour éliminer les chutes de FPS inexpliquées.

### 🖥️ Monitoring (Overlay)
* **OVERLAY :** Affiche un tableau de bord compact en jeu (PERF SCORE, PING, JITTER, STABILITÉ).
* **INFO LOGICIEL / SYSTÈME :** Affiche les détails complets de votre matériel (CPU, GPU, RAM).

---

## 📊 Comprendre le PERF SCORE

| Score | État | Ressenti |
| :--- | :--- | :--- |
| **0 - 150** | **LOW** | Système lourd, Input Lag perceptible. |
| **150 - 300** | **OPTIMAL** | Configuration saine pour le gaming. |
| **300 - 500** | **ULTRA** | Zone FRC. Réactivité quasi-instantanée. |
| **500+** | **GOD MODE** | Performance Maximale. |

---

## 🔗 Liens & Réseaux

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

---

## 🛡️ Sécurité
* **Zéro Bloatware :** Utilise uniquement les ressources natives de Windows (.NET/PowerShell).
* **Code Sécurisé :** Distribué sous forme compilée pour garantir l'intégrité des scripts.

**Développé par [Mynotorr](https://github.com/mynotorr)**
