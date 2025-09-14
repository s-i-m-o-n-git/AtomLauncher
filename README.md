<h1 align="center">Atom Launcher</h1>
<p align="center"><img src="./app/assets/images/SealCircle.png" width="150px" height="150px" alt="Atom Launcher logo"></p>

<em><h5 align="center">(based on Helios Launcher, formerly Electron Launcher)</h5></em>

<p align="center">
  <a href="https://github.com/s-i-m-o-n-git/AtomLauncher/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/s-i-m-o-n-git/AtomLauncher/build.yml?branch=main&style=for-the-badge" alt="gh actions">
  </a>
  <a href="https://github.com/s-i-m-o-n-git/AtomLauncher/releases">
    <img src="https://img.shields.io/github/downloads/s-i-m-o-n-git/AtomLauncher/total.svg?style=for-the-badge" alt="downloads">
  </a>
</p>

<p align="center">Rejoignez des serveurs moddés sans vous soucier d'installer Java, Forge ou autres mods. Le launcher s’occupe de tout pour vous.</p>

---

## 📦 Distribution des fichiers

👉 Les fichiers nécessaires (mods, configs, ressources, etc.) sont disponibles dans un dépôt séparé :  
➡️ [AtomLauncherDistro](https://github.com/s-i-m-o-n-git/AtomLauncherDistro)  

Le launcher télécharge automatiquement ces fichiers pour préparer votre jeu.

---

## ✨ Fonctionnalités principales

- 🔒 **Gestion complète des comptes**  
  - Support Microsoft (OAuth 2.0) et Mojang (Yggdrasil).  
  - Multi-comptes, avec bascule facile.  

- 📂 **Gestion efficace des fichiers**  
  - Téléchargement et validation automatique des assets.  
  - Les fichiers corrompus ou manquants sont re-téléchargés.  

- ☕ **Java automatique**  
  - Pas besoin d’installer Java manuellement.  
  - Le launcher installe la bonne version si nécessaire.  

- 📰 **Flux d’actualités intégré** directement dans le launcher.  

- ⚙️ **Panneau de paramètres intuitif**, incluant la gestion de Java.  

- 🚀 **Mises à jour automatiques** du launcher.  

- 📊 **Status Mojang intégré** + affichage du nombre de joueurs connectés sur le serveur.  

---

## 📥 Téléchargement

Téléchargez la dernière version depuis la section [Releases](https://github.com/s-i-m-o-n-git/AtomLauncher/releases).  

| Plateforme | Fichier |
|------------|---------|
| Windows x64 | `Atom-Launcher-setup-VERSION.exe` |
| macOS x64   | `Atom-Launcher-setup-VERSION-x64.dmg` |
| macOS arm64 | `Atom-Launcher-setup-VERSION-arm64.dmg` |
| Linux x64   | `Atom-Launcher-setup-VERSION.AppImage` |

---

## 🛠️ Développement

### Prérequis
- [Node.js](https://nodejs.org/) v20+

### Installation
```bash
git clone https://github.com/s-i-m-o-n-git/AtomLauncher.git
cd AtomLauncher
npm install
```

### Lancer en mode dev
```bash
npm start
```

### Générer un installeur
```bash
npm run dist
```

---

## 🙏 Crédits

- Basé sur [Helios Launcher](https://github.com/dscalzi/HeliosLauncher) ❤️  
- Merci à la communauté open source.  

---

⭐ Si vous aimez le projet, pensez à mettre une **star** sur le repo !
