CAPRI AI — prototype PWA

Contenu :
- index.html : interface et fonctions de base
- manifest.json : métadonnées pour installation comme application web
- sw.js : cache hors ligne simple

Important :
Cette version est un prototype gratuit. Elle propose une interface, la synthèse vocale du navigateur, une tentative de reconnaissance vocale (selon compatibilité Safari) et une mémoire locale sur l'appareil.
Elle ne contient pas encore de véritable modèle d'IA ni une mémoire synchronisée, et la recherche Web ouvre un nouvel onglet.

Pour l'installer sur iPhone :
1. Héberger ces fichiers sur un site HTTPS (par exemple GitHub Pages).
2. Ouvrir l'adresse du site dans Safari.
3. Toucher Partager > Sur l'écran d'accueil > Ajouter.

Ne place jamais de clé API secrète dans index.html. Une vraie IA nécessitera un service côté serveur et peut entraîner des frais selon l'usage.
