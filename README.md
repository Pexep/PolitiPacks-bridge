# PolitiPacks-bridge

Un ressource pack vide permettant de facilement modifier les textures des items de Politicraft pour les créateurs de ressources packs.

Items pris en compte :
- Les Certificats (y compris les certificats universels)
- Les Gemmes et Lingots du passe

## Installation
1. Télécharger le pack de ressources [ici](https://github.com/Pexep/PolitiPacks-bridge/releases/latest).
2. Placer le fichier `.zip` dans le dossier `resourcepacks` de votre installation
3. Faire pareil pour le ressource pack contenant les textures de votre choix qui s'appuie sur PolitiPacks-bridge
4. Activer les deux packs de ressources dans le menu de sélection des packs de ressources de Minecraft, en veillant à ce que **PolitiPacks-bridge soit au-dessus** du pack de ressources contenant les textures personnalisées.

## Utilisation pour les créateurs de ressources packs
Il n'y a pas grand chose à faire, il suffit de créer un pack de ressources en mettant les textures personnalisées dans le bon dossier et avec le bon nom.
**Pas de majuscules ni de caractères spéciaux dans les noms de fichiers !**

Le dossier racine de toutes vos textures doit être `assets/minecraft/textures/item/`.

Pour les certificats :
- placez les dans le sous-dossier `certificats/`
- nommez les `certificat_[nom du métier]_tier_[numéro du tier].png` (ex: `certificat_fermier_tier_2.png`)

Pour les objets du passe :
- placez les dans le sous-dossier `passe/`
- les noms :
  - `gemme_du_politipasse.png` pour la gemme du passe
  - `lingot_du_politipasse.png` pour le lingot du passe