# NEON ARENA

Un mini FPS rétro, autonome et jouable dans le navigateur, sans dépendance ni étape de compilation.

## Jouer en local

Ouvre `index.html` dans un navigateur récent, ou sers le dossier avec un serveur HTTP local.

## Commandes

- **PC :** ZQSD ou WASD pour se déplacer, flèches gauche/droite pour tourner, souris pour viser, clic ou Espace pour tirer.
- **Mobile :** commandes tactiles pour avancer, reculer et tourner ; glisse sur l’arène pour viser et utilise le bouton de tir.
- La touche **Échap** ou le bouton **Pause** met la partie en pause.

Les drones poursuivent le joueur. Élimine-les pour passer à la vague suivante ; le record est conservé dans le navigateur.

## Déploiement GitHub Pages

Le workflow `.github/workflows/static.yml` publie automatiquement le site sur chaque push vers `main` et peut aussi être lancé manuellement depuis l’onglet **Actions**. Dans **Settings → Pages**, sélectionne **GitHub Actions** comme source de déploiement.

La page d’accueil du site est `index.html`.
