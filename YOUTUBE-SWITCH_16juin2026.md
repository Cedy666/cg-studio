# Bascule YouTube → @CedricGodinStudio — 16 juin 2026

Tâche planifiée exécutée automatiquement (Cédric absent).

## ✅ Fait automatiquement
- `index.html` (ligne 594) : lien YouTube → `https://www.youtube.com/@CedricGodinStudio`
- `CLAUDE.md` (ligne 74) : référence YouTube mise à jour
- Vérifié : plus aucune occurrence de l'ancien handle `@CG.studio-j5v` dans le repo

## ⛔ À faire par Cédric (impossible en autonome)

**1 + 2 — Nom & handle YouTube** (nécessite connexion YouTube Studio, présence requise)
- YouTube Studio → Paramètres → Chaîne → Infos de base
- Nom : "CG studio" → **Cédric Godin**
- Handle : @CG.studio-j5v → **@CedricGodinStudio**

**4 — Push GitHub** (le `.git` est inaccessible depuis le sandbox + credentials GitHub côté Mac)
Les fichiers sont déjà modifiés dans le dossier. Pour pusher, dans le Terminal :
```
cd ~/Documents/Claude/Projects/MyWebsite
git add index.html CLAUDE.md YOUTUBE-SWITCH_16juin2026.md
git commit -m "YouTube: bascule vers @CedricGodinStudio"
git push origin main
```

⚠️ Note : un fichier `.git/HEAD.lock` traîne depuis le 1er juin. S'il bloque le commit, supprime-le :
`rm -f .git/HEAD.lock`
