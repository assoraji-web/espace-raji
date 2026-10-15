# Icône « Espace RAJI » sur les téléphones — guide de mise en ligne (une seule fois)

Ce dossier est une petite page web statique. Hébergée gratuitement sur GitHub Pages, elle permet à chaque membre
d'installer une icône RAJI sur son téléphone ; un toucher sur l'icône ouvre l'Espace RAJI.

## 1. Récupérer le lien de l'Espace RAJI
Apps Script → Déployer → Gérer les déploiements → copiez l'URL « Application Web » (elle finit par `/exec`).

## 2. Renseigner le lien
Ouvrez `config.js` et remplacez `COLLER_ICI_LE_LIEN_ESPACE_RAJI` par ce lien (entre les guillemets).

## 3. Mettre en ligne sur GitHub Pages
1. Connectez-vous à github.com (compte personnel ou de l'association) → **New repository** → nom : `espace-raji` → **Public** → Create.
2. **Add file → Upload files** : glissez TOUT le contenu de ce dossier (index.html, config.js, manifest.webmanifest, sw.js, dossier icons) → **Commit changes**.
3. **Settings → Pages** → Source : *Deploy from a branch* → Branch : `main` / `(root)` → Save.
4. Après 1 à 2 minutes, la page est disponible à : `https://VOTRE-NOM.github.io/espace-raji/`

## 4. Diffuser
Envoyez ce lien d'installation aux membres (WhatsApp, e-mail). Chacun l'ouvre sur son téléphone et suit les 3 étapes affichées
(Android : Chrome ; iPhone : Safari). L'icône RAJI est alors sur l'écran d'accueil.

## Limites à connaître (non vérifiées sur vos téléphones)
- Je n'ai pas pu tester sur de vrais téléphones. Le comportement varie selon la marque, la version d'Android/iOS et le navigateur.
- L'Espace RAJI reste hébergé par Google : à l'ouverture, certains téléphones peuvent afficher une fine barre d'adresse en haut.
- Si l'adresse GitHub change, il faut redonner le nouveau lien d'installation.
- Le lien /exec change si l'on crée un *nouveau* déploiement ; modifiez alors `config.js`.
