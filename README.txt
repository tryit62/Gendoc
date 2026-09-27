GENDOC V10 STABLE 1.0 — PWA

Contenu à placer à la racine du dépôt GitHub Pages GenDoc :
- index.html
- manifest.webmanifest
- sw.js

IMPORTANT
1. Une PWA et son système de mise à jour nécessitent HTTPS/localhost. Ouvrir index.html directement depuis Fichiers ne peut pas activer le service worker.
2. Après mise en ligne sur GitHub Pages, ouvrir l’URL dans Safari puis Partager > Sur l’écran d’accueil.
3. Les données GenDoc sont stockées dans IndexedDB pour cette origine web. Ne change pas d’URL/domaine si tu veux conserver les données locales.
4. Avant toute grosse mise à jour, exporter aussi une sauvegarde .gendoc.
5. Pour une future version, modifier VERSION dans sw.js (ex. gendoc-v10.0.1) avant déploiement.
