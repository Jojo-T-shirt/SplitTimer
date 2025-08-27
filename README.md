# Fractionné Running — PWA

Web‑app mobile pour faire du fractionné (course à pied) — gros chronos, annonces vocales, bip, vibration, presets (30/30, 30/15×12, Tabata, Pyramide), écran actif, mode hors‑ligne.

## Déploiement rapide (GitHub Pages)

1. Crée un repo **fractionne-pwa** sur GitHub.
2. Dépose les fichiers de ce dossier (`index.html`, `service-worker.js`, `manifest.webmanifest`, `offline.html`, dossier `icons/`).
3. Dans **Settings → Pages**, choisis **Deploy from a branch**, branche **main**, dossier **/** (root).
4. Attends la publication, puis ouvre l’URL GitHub Pages. Sur mobile, tu pourras **Installer l’app** depuis le bouton ou le menu du navigateur.

> Remarque : Les chemins sont relatifs (`./`), donc ça marche dans un sous-dossier GitHub Pages.

## Utilisation

- Régle les temps (échauffement, effort, repos, répétitions, retour au calme).
- Choisis un preset (30/30, 30/15×12, 1’/1’×8, Tabata 20/10×8, Pyramide…).
- Appuie **Démarrer**. L’app annonce les phases, vibre, et garde l’écran allumé (si supporté).
- Pause/reprise avec le bouton *Pause* ou **appui long** sur le chrono.

## Fichiers

- `index.html` — l’app (UI + logique)
- `service-worker.js` — cache offline
- `manifest.webmanifest` — PWA manifest + icônes
- `offline.html` — page secours hors-ligne
- `icons/icon-192.png`, `icons/icon-512.png` — icônes
