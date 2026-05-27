# HERMES V7 — Patrimoine & Trading

## 📦 Contenu du dossier

- **index.html** — l’application complète (152 KB)
- **manifest.json** — fichier PWA (installable)
- **sw.js** — service worker (offline)

## 🚀 Utilisation

### Test rapide

1. Décompresse le dossier
1. Double-clique sur `index.html` → s’ouvre dans ton navigateur
1. C’est tout. Aucun serveur, aucune installation.

### Installation en PWA (recommandé)

Pour profiter du mode offline + raccourci écran d’accueil, héberge les 3 fichiers sur un serveur ou utilise un service gratuit (GitHub Pages, Netlify, Vercel…) :

**iPhone / iPad** (Safari)

- Ouvre l’URL dans Safari
- Bouton Partager (carré + flèche)
- “Sur l’écran d’accueil”

**Android** (Chrome)

- Ouvre l’URL dans Chrome
- Menu ⋮ → “Installer l’application”

**Ordinateur** (Chrome, Edge)

- Ouvre l’URL
- Icône ⊕ dans la barre d’adresse
- “Installer”

## 📋 Fonctionnalités

### 5 onglets principaux

1. **🏠 Accueil** — KPI, suggestions intelligentes, accès rapides
1. **💼 Portefeuille** — Apports, DCA mensuel, bénéficiaires (%), achats, profil de risque (tout-en-un)
1. **🎯 Trading** — Pré-trade automatisé + journal + statistiques
1. **📚 Apprendre** — 8 sections de cours intégrés
1. **⚙️ Réglages** — Niveau, accessibilité, ressources, backup

### 8 sections de cours

- 📖 Introduction
- 💎 Types d’actifs (ETF, actions, obligations, immo, crypto, commos, forex, dérivés, cash)
- 🎩 **Méthode Warren Buffett** — bilan, compte de résultat, cash flow, 10 ratios, moats, DCF, checklist
- 🏛 8 Piliers du trading
- 📈 Patterns chartistes (12)
- 🧮 **5 simulateurs interactifs** (intérêts composés, DCA, position sizing, DCF Buffett, rente Trinity)
- 📖 Glossaire 3 niveaux
- 📑 Fiscalité française

### Accessibilité & inclusion

- 🔤 4 tailles de texte (85%, 100%, 115%, 130%)
- 🌗 Mode sombre / clair
- 🎨 Mode contraste élevé (malvoyants)
- 🎓 3 niveaux d’expertise (Débutant / Inter / Expert) — adapte le contenu
- ⌨️ Navigation clavier complète, ARIA labels, focus visible
- 📱 Mobile-first, tables → cards automatique

### Ressources éditables

Dans Réglages → Mes ressources, tu renseignes tes liens cloud :

- Drive
- Cours / annexes
- Comptes brokers
- Simulateurs externes
- Documents fiscaux
  Modifiables à tout moment, exportés avec le backup JSON.

## 💾 Sauvegarde

Tes données sont stockées localement (localStorage). Pour migrer entre appareils :

- Réglages → “Télécharger sauvegarde JSON”
- Sur l’autre appareil : “Restaurer depuis JSON”

Le backup inclut : apports, bénéficiaires, produits, achats, trades, profil, ressources, progression cours.

## 🔒 Confidentialité

- **100% local** — aucun envoi sur internet
- **Aucun tracker**
- **Pas de compte requis**
- **Fonctionne offline**

## 📞 Support

Si un lien ne fonctionne pas ou si tu veux modifier quelque chose, les liens internes sont dans le code (cherche `goTab` ou `setLearn`).

Toutes tes ressources cloud sont stockées dans **Réglages → Mes ressources** et modifiables à tout moment.
