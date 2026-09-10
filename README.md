# Appartement Lumière — visite 3D au scroll (démo a.SYNC)

POC d'expérience web où la caméra **marche dans un appartement** au fil du scroll : on avance, on **tourne**, on **change de pièce** (séjour → cuisine → chambre → salle à manger), comme une vraie visite. 3D **temps réel** (WebGL) → net à n'importe quelle taille, fluide, navigable.

- **Techno** : Three.js (r166), scroll fluide Lenis, courbe caméra Catmull-Rom (13 waypoints), tonemapping ACES Filmic + environnement HDRI, mobilier procédural, ombres douces.
- **Single file** : tout est dans `index.html`, aucun build. S'ouvre en local ou se sert en statique.
- **Mobile** : scroll tactile natif, HUD lisible.

Base : template `house` du skill `webdesign-3d-scroll-experience` de Herman, personnalisé en appartement pour a.SYNC.

> Démo interne a.SYNC. Le photoréalisme se pousse ensuite en branchant un vrai modèle 3D (glTF) à la place du mobilier procédural.
