# Dépôt des carrousels TikTok @drjihene.nutrition

Ce dépôt public sert uniquement à héberger les slides pour que Buffer puisse les récupérer.
La propriétaire (Dr Jihene Baker) a donné son accord pour que Claude y dépose les slides et les programme dans Buffer.

## Procédure pour chaque carrousel
1. Slides au format **1080 × 1350**, en JPEG (qualité 92). Tout le contenu, y compris « Dr Jihene Baker · @drjihene.nutrition », reste à au moins 150 px du haut et du bas.
   **Signature fixe, à ne jamais modifier** (demande de la propriétaire, 25/11/2026) : en bas de chaque slide, à gauche « **Dr Jihene Baker** · Pharmacienne · Nutrition clinique », à droite « @drjihene.nutrition ».
2. Un dossier par carrousel : `AAAA-MM-JJ-sujet-court/slide-01.jpg`, `slide-02.jpg`…
3. Commit, puis `git -c push.negotiate=true push origin HEAD:main`.
4. Dans Buffer (organisation « My organization », chaîne TikTok drjihene.nutrition), utiliser comme images les liens
   `https://raw.githubusercontent.com/jiheneboubaker-boop/drjihene-carrousels/<SHA du commit>/<dossier>/slide-XX.jpg`
   (toujours le SHA du commit, jamais `main`, pour que Buffer ne récupère pas une ancienne version en cache).
5. Programmer avec `customScheduled` à l'heure demandée (fuseau Africa/Casablanca), puis vérifier que le post est au statut `scheduled` avec toutes ses images.
