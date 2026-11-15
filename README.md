# Vexa Studio

Site web du Studio Variantes : variantes 2 (même vidéo, autre couleur de texte) et export direct dans Google Drive.

## Mise en ligne (GitHub Pages, gratuit)
1. Dépose `index.html` (et ce README) à la racine du dépôt `vexa-studio` (dépôt **Public**).
2. **Settings → Pages** → *Deploy from a branch* → branche **main**, dossier **/ (root)** → **Save**.
3. Le site est en ligne à `https://galaupjules-glitch.github.io/Vexa-studio/`.

## Réglages Google Cloud (une seule fois)
- Activer **Google Picker API** et **Generative Language API** (Gemini).
- Créer un **ID client OAuth « Application Web »** avec l'origine `https://galaupjules-glitch.github.io`.
- Créer une **clé API**, limitée au site `https://galaupjules-glitch.github.io/*` et aux deux API ci-dessus.
- Coller l'ID client et la clé dans **⚙ Réglages** du site.
