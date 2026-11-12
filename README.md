# Éditeur ASA – CFDT EFRP Réunion (version web / mobile)

Mise en ligne sur GitHub Pages :
1. Créer un dépôt (ex. `editeur-asa`) et y déposer tous les fichiers de ce dossier à la racine.
2. Settings → Pages → Source : branche `main`, dossier `/ (root)` → Save.
3. Ouvrir l'adresse https://<votre-compte>.github.io/editeur-asa/ sur le téléphone.
4. Chrome Android : menu ⋮ → « Ajouter à l'écran d'accueil ». iPhone : Partager → « Sur l'écran d'accueil ».

Aucune signature n'est intégrée au fichier : la charger une fois sur chaque appareil (Réglages → Signature). Elle est stockée dans le navigateur de l'appareil et n'est jamais envoyée.

Pour mettre à jour : remplacer `index.html` dans le dépôt et, dans `sw.js`, changer `asa-cfdt-v1` en `asa-cfdt-v2` (etc.) pour forcer le rafraîchissement des appareils.
