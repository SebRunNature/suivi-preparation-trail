# 🏔️ Suivi Préparation Trail — Seb Run Nature

> Un dashboard trail **100% gratuit, hors ligne et privé** — un seul fichier HTML, aucune installation.

![Dashboard Trail Preview](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhrfu2zq2g3-ATnf0ZYCeg5Kg8qqDQeDvS90-6froBJuEgnX9WDnH__5xiYBtjeyxYCMIsvog_uxip0aoW0RCnfaVA2xREZzAlvx5FBCdg5n40MjaRiM1ufejrYeKJHqPQvIUUPphqiepEwCZaVE-OIj1X-f1OeE259W5FJdcZhe_NYAn2Gj9Wz8-svP34/w640-h248/suivi%20preparation%20trail%201.JPG)

---

## ⬇️ Téléchargement

👉 **[Ouvrir le fichier HTML](https://github.com/SebRunNature/suivi-preparation-trail/raw/main/Suivi_Preparation_Trail_v9.html)**


> Ouvrez le fichier directement dans votre navigateur (Chrome, Firefox, Edge, Safari) — aucune installation ni compte requis.
Si vous avez copié le code brut : Collez-le dans un éditeur de texte (Notepad++, Bloc-notes…). Enregistrez avec l’extension .html.
Double-cliquez sur le fichier pour l’ouvrir. Consultez les instructions détaillées ci-dessous ou sur mon blog pour la suite.


## 🎯 Pourquoi cet outil ?

J'en avais assez de donner accès à mes données d'entraînement à des plateformes tierces, et de perdre du temps à scroller le fil d'actualité Strava au lieu d'analyser ma propre préparation. Ce dashboard est né de ce besoin simple : **un outil personnel, rapide, privé, qui reste chez toi**.

Tes données ne quittent jamais ton ordinateur. Pas de cloud, pas de compte, pas de publicité.

---

## ✨ Fonctionnalités

### 📋 Journal des séances
- Enregistre **Course, Vélo Home Trainer, Renforcement, Cardio**
- Distance, D+, durée, vitesse/allure calculées automatiquement
- RPE (effort perçu 1–10), BPM moyen, nutrition, notes libres

### 📂 Import GPX automatique
- Importe directement depuis ta montre GPS (Garmin, Polar, Suunto, Coros…)
- Calcul automatique distance, D+, durée, allure

### 📊 Récapitulatif Global
- Km totaux, D+ cumulé, heures par activité, vitesse moyenne
- **Moyenne RPE colorée** avec règle 80/20 (🟢 🟡 🔴)
- BPM moyen global

### 🎯 Trail Objectif
- Définis ton trail cible (nom, URL, distance, D+, date)
- **Bandeau de préparation** 🟢🟡🔴 basé sur la moyenne des 4 dernières semaines
- Table de référence intégrée pour 10 / 20 / 30 / 40 / 50 / 100 / 150 km

### 📈 Graphique hebdomadaire
- Histogramme des 8 dernières semaines
- Km de course + D+ en deux barres côte à côte
- 3 onglets : Km / D+ / Les deux

### 🔍 Filtres & Tri
- Filtre par type, période, RPE
- Tri par date, distance, D+, RPE
- Compteur de séances affichées

### 🏔️ Générateur d'image style Coros
- Image de partage **1080×1080 px** avec stats, photo de fond, logo
- Téléchargeable en `.jpg`

### 🎬 Générateur de vidéo animée
- Vidéo animée **6.5 secondes** avec tes stats
- Écran signature final avec logo et URL
- Téléchargeable en `.webm`

### 🖼️ Banque de photos personnelle
- Stockage dans **IndexedDB** (capacité illimitée)
- 3 niveaux de compression : Haute / Standard / Compacte
- Utilisées automatiquement comme fonds d'image et vidéo

### 💾 Sauvegarde complète
- Export tout-en-un : séances + photos + titre → fichier `.json`
- Restauration complète en un clic
- Rappel automatique si pas de sauvegarde depuis 7 jours

### ⬇️ Export multi-formats
- **JSON** — sauvegarde complète ou séances uniquement
- **CSV** — compatible Excel / LibreOffice avec BOM UTF-8
- **PDF** — mise en page imprimable avec synthèse et tableau

### 🌙 Mode sombre
- Automatique (suit les préférences système)
- Bouton de bascule manuel 🌙 / ☀️
- Mémorisé entre les sessions

---

## 🚀 Utilisation

1. **Télécharge** le fichier `Suivi_Preparation_Trail.html`
2. **Ouvre-le** dans ton navigateur (double-clic ou glisser-déposer)
3. **C'est tout.** Commence à enregistrer tes séances

> ⚠️ **Important** : les données sont stockées localement dans ton navigateur. Si tu vides ton cache ou changes d'appareil, utilise le bouton **💾 Sauvegarde complète** pour ne rien perdre.

---

## 🔒 Confidentialité

- **Aucune donnée n'est envoyée sur internet**
- Les séances sont stockées dans le `localStorage` de ton navigateur
- Les photos sont stockées dans `IndexedDB` (base de données locale)
- Tout reste sur ton ordinateur, uniquement

---

## 🛠️ Personnalisation

Le fichier est un HTML autonome, entièrement lisible et modifiable dans n'importe quel éditeur de texte (VS Code, Notepad++…). Tu peux :
- Modifier les couleurs (variables CSS au début du fichier)
- Adapter les tables de référence d'entraînement
- Ajouter tes propres champs si tu t'y connais en HTML/JS

---

## 📖 Article de blog

Pour en savoir plus sur la philosophie de l'outil et comment l'utiliser :  
👉 [Mon Dashboard Trail – Suis ta préparation comme un pro](https://www.seb-run-nature.com/)

---

## 📋 Compatibilité

| Navigateur | Support |
|------------|---------|
| Chrome 90+ | ✅ Complet |
| Firefox 112+ | ✅ Complet |
| Edge 90+ | ✅ Complet |
| Safari 16+ | ✅ Complet |
| Mobile (Chrome/Safari) | ✅ Complet |

> La génération vidéo (`.webm`) nécessite un navigateur supportant l'API `MediaRecorder` — disponible sur tous les navigateurs modernes.

---

## 👤 Auteur

**Sébastien** — Trailer amateur passionné, Luxembourg 🇱🇺

🌿 Blog : [www.seb-run-nature.com](https://www.seb-run-nature.com/)  
📧 Contact : via le blog

---

## 📄 Licence

Cet outil est partagé **gratuitement** pour la communauté trail. Tu peux l'utiliser librement, le modifier et le partager à condition de mentionner la source originale.

---

*Créé avec ❤️ par Seb Run Nature · Données privées, stockées localement · Aucune installation*
