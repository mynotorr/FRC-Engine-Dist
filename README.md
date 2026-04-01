# 🚀 FRC Engine v1.0.6 - Optimization Suite

## 👀 Preview
<p align="center">
  <img src="https://raw.githubusercontent.com/mynotorr/FRC-Engine-Dist/main/preview.png" alt="FRC Engine Preview" width="800">
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/mynotorr/FRC-Engine-Dist?style=for-the-badge&color=cyan">
  <img src="https://img.shields.io/github/downloads/mynotorr/FRC-Engine-Dist/total?style=for-the-badge&color=green">
  <img src="https://img.shields.io/badge/Language-PowerShell-blue?style=for-the-badge&logo=powershell">
</p>

**FRC Engine** est une suite d'optimisation de "bas niveau" conçue pour transformer Windows en une plateforme de jeu ultra-réactive. Contrairement aux simples nettoyeurs de fichiers, FRC Engine agit directement sur le **Kernel (noyau)** pour réduire l'**Input Lag** et stabiliser les **Frametimes**.

---

## 🛠️ Pourquoi laisser FRC allumé ? (IMPORTANT)
Pour une efficacité maximale, **FRC ENGINE DOIT RESTER OUVERT PENDANT QUE VOUS JOUEZ** :
* **AUTO-CLEAN :** Sans lui, Windows accumule des "déchets" en RAM qui causent des micro-saccades (*stutters*) lors de vos mouvements de souris rapides. Il nettoie votre mémoire toutes les 6 secondes.
* **GAME FOCUS :** Si FRC est fermé, Windows reprend ses mauvaises habitudes et traite les tâches de fond avant votre jeu. Game Focus force votre CPU à se concentrer uniquement sur votre performance.

---

## ✨ Fonctionnalités Majeures

### ⚡ Optimisation Kernel & Système
* **38 Tweaks Registre :** Ajustement du `Win32PrioritySeparation`, désactivation du HPET et optimisation des files d'attente.
* **Deep Clean :** Nettoyage profond des fichiers temporaires et résidus de mises à jour Windows.
* **Shader Cache Cleaner :** Nettoie les caches GPU (NVIDIA/AMD) pour forcer une reconstruction propre et fluide des textures.

### 🖥️ Overlay Intelligent
* **PERF SCORE :** Un indice exclusif mesurant la réactivité réelle du Kernel (0-500+).
* **Latence Réseau :** Monitoring en temps réel avec calcul du Jitter (stabilité du ping).

---

## 📊 Comprendre le PERF SCORE

| Score | État | Ressenti |
| :--- | :--- | :--- |
| **0 - 150** | **LOW** | Système lourd, Input Lag perceptible. |
| **150 - 300** | **OPTIMAL** | Configuration saine pour le gaming. |
| **300 - 500** | **ULTRA** | Zone FRC. Réactivité instantanée. |
| **500+** | **GOD MODE** | Performance E-Sport. Latence Kernel minimale. |

---

## 🚀 Installation & Utilisation

1.  **Téléchargement :** Récupérez la dernière version dans l'onglet **[Releases](https://github.com/mynotorr/FRC-Engine-Dist/releases)**.
2.  **Lancer l'Optimisation :** Cliquez sur le bouton principal.
3.  **Redémarrage (MANDATAIRE) :** Obligatoire pour injecter les modifications dans le Kernel.
4.  **Mode Jeu :** Lancez FRC, activez **AUTO-CLEAN** + **GAME FOCUS**, et lancez votre jeu.

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
* **Bouton Rollback :** Restaure les paramètres Windows d'origine en un clic.
* **Zéro Bloatware :** Utilise uniquement les ressources natives de Windows (.NET/PowerShell).

**Développé par [Mynotorr](https://github.com/mynotorr)**

---
*Avis de non-responsabilité : L'utilisation d'outils d'optimisation système se fait à vos propres risques. Bien qu'un système de Rollback soit présent, effectuez toujours une sauvegarde de vos données importantes.*
