---
hide:
  - toc
---

<!-- https://steamcommunity.com/sharedfiles/filedetails/?id=2963174023 -->

L'animation exprime le mouvement en changeant continuellement d'images pour chaque image.

Chaque cadre est une zone (rectangle) dans le canevas. <br />
Tous les cadres sont affichés dans le canevas.

Lorsque vous ouvrez un fichier gif ou webp animé, le canevas est créé avec l'animation prête à être lue. <br />
Cependant, si la taille du canevas est trop grande, l'animation ne sera pas créée.

![animation](./image/animation.png)

Par exemple, dans ce canevas, chaque image de l'animation est une zone carrée avec des nombres de 1 à 13. <br />
Lorsque vous jouez l'animation, elle se déroulera comme suit.

![13_frame](./image/13_frame.gif)

### Comment créer des animations

![canvas](./image/animation_canvas.png)

Tout d'abord, créez un canevas qui ressemble à ceci. <br />
Ensuite, ouvrez la fenêtre "Animation" en cliquant sur le bouton "Fenêtre d'animations" du menu "Canevas".

![step](./image/animation_step.png)

Vous créez 13 cadres.

![frame](./image/animation_frame.png)

Vous pouvez spécifier la position en bas à gauche de chaque cadre. <br />
__"1, X 0, Y 150"__ signifie que la position en bas à gauche de la première image est (0, 150). <br />
La position en bas à gauche du canevas est (0, 0). <br />
Dans cet exemple, chaque cadre a une largeur et une hauteur de 50 px. <br />
Lorsqu'un cadre est sélectionné, un cadre rectangulaire bleu s'affiche dans le canevas.

Si la case __"Choisissez la couleur de l'image intégrée"__ est cochée, l'animation jouera avec l'apparence actuelle du canevas. <br />
Si cette case à cocher est désactivée, l'animation sera lue avec uniquement l'apparence du calque spécifié.

L'animation sera jouée en cliquant sur le bouton __"Démarrer"__. <br />
Vous pouvez modifier la position et la taille de l'animation lue en sélectionnant l'outil d'animation.

![tool](./image/animation_tool.png)

Vous pouvez enregistrer l'animation sous forme de fichier gif ou webp. <br />
Étant donné que les fichiers gif ont un nombre limité de couleurs, vous ne pouvez enregistrer en tant que fichier gif que lorsque le calque de Pixel-art est sélectionné. <br />
Dans ce cas, vous devez dessiner l'animation dans le calque de Pixel-art.
