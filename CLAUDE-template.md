# CLAUDE.md

This file provides guidance to Claude Code when working with this repository.

## 🎯 Project Overview

**[NOM DU PROJET]** — [Description en une phrase]

**Owner:** Maxime Santilli  
**Status:** [Discovery / MVP / Active / Maintenance]  
**Stack:** [ex: Python 3, FastAPI, Google APIs]  
**URL prod:** [si applicable]  

---

## ⚡ Commands
```bash
# Setup
[commande d'installation]

# Dev
[commande pour lancer en local]

# Deploy
[commande de déploiement]
```

---

## 📁 Structure
```
[nom-projet]/
├── CLAUDE.md
├── [fichier principal]
├── .env                ← ne jamais committer
├── .env.example        ← toujours maintenir à jour
└── .gitignore
```

---

## 🏗️ Architecture

[Description courte : monolith / microservices / script standalone / etc.]

### Fichiers clés
- `[fichier]` — [rôle]
- `[fichier]` — [rôle]

### Variables d'environnement importantes
- `[VAR]` — [description]

---

## 🚫 Ne jamais modifier sans confirmation explicite

- `.env`
- `[fichiers credentials]`
- `[fichiers critiques spécifiques au projet]`

---

## 🧠 Règles pour Claude Code

1. Toujours demander confirmation avant de modifier plus de 50 lignes
2. Ne jamais hardcoder de clés API — utiliser `.env`
3. Proposer un plan étape par étape avant tout refactor
4. Répondre en français, code en anglais
5. Expliquer le "pourquoi" pas seulement le "comment"
6. [Règle spécifique au projet]
7. [Règle spécifique au projet]

---

## 🔗 Ressources

- [Lien doc API utilisée]
- [Lien dashboard prod]
- [Lien repo GitHub]