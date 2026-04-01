# Claude Templates

Templates de démarrage pour initialiser proprement un projet avec Claude Code.

## 🚀 Workflow — Nouveau projet
```bash
# 1. Créer et entrer dans le projet
mkdir mon-nouveau-projet
cd mon-nouveau-projet

# 2. Récupérer le template CLAUDE.md
curl -o CLAUDE.md https://raw.githubusercontent.com/maximegit-prog/claude-templates/main/CLAUDE-template.md

# 3. Remplir les [PLACEHOLDERS] dans CLAUDE.md
# Nom du projet, stack, fichiers clés, règles spécifiques — 2 minutes max

# 4. Lancer Claude Code
claude
```

Dans Claude Code :
```
/init
```

Claude complète automatiquement la partie technique en analysant ton code.

## ⚠️ Pourquoi cet ordre ?

- `curl` en premier → Claude Code lit ton CLAUDE.md dès le démarrage
- `/init` en second → il complète sans écraser ton template

---

## 📁 Fichiers disponibles

| Fichier | Description |
|---------|-------------|
| `CLAUDE-template.md` | Template universel CLAUDE.md |

---

## 🧠 User Memory globale

Tes règles personnelles sont dans `~/.claude/CLAUDE.md` — elles s'appliquent
automatiquement à tous tes projets sans rien faire.

Pour les éditer :
```
/memory → 2. User memory
```

---

## ➕ Ajouter un template
```bash
cd ~/Desktop/AI/templates
# Crée ton nouveau fichier template
git add .
git commit -m "Add [nom] template"
git push
```