# Six Tuiles

[Télécharger l’APK](https://github.com/Zachiran42/six-tuiles/releases/latest/download/six-tuiles-0.1.0.apk) · [Versions](https://github.com/Zachiran42/six-tuiles/releases) · [Page du jeu](https://zachiran42.github.io/six-tuiles/)

Prototype Android8+, natif et universel, sans publicité ni permission, hors ligne. Licence MIT.

Six placements sur une grille4×4 : relie l’entrée gauche (troisième ligne) à la sortie droite (première ligne). Choisis une des deux tuiles, tourne-la puis touche une case libre et POSER. Les ouvertures voisines doivent correspondre. Deux cases dorées rapportent40points chacune si reliées au chemin gagnant. Chaque série propose un itinéraire réalisable. REFAIRE démarre une nouvelle grille.

La tentative est enregistrée après chaque coup validé ; la pause et le record sont locaux. APK de développement, aucun téléphone physique testé.

## Compiler
Copier le modèle .toolchain.example.json en .toolchain.json avec JDK21, AndroidSDK36 et BuildTools36. Définir MINIGAMES_KEYSTORE_PASSWORD dans l’environnement et fournir une clé externe à scripts/build.ps1 -KeyStore ... -KeyAlias ... . Ne jamais publier les clés.

## Dans Cercle

Dans « Ajouter depuis GitHub », coller `https://github.com/Zachiran42/six-tuiles`. La dernière Release contient un seul APK, signé, universel et sans permission Internet.

## Compilation

Copier `.toolchain.example.json` vers `.toolchain.json`, renseigner JDK21, Android SDK36 et Build Tools, puis définir `MINIGAMES_KEYSTORE_PASSWORD` dans l’environnement. Utiliser `scripts/build.ps1 -KeyStore C:/cles/jeu.keystore -KeyAlias votre-alias`. Garder les clés hors du dépôt.
