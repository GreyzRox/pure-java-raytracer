# Rapport écrit du TME 6

## Question 2

#### Les principaux éléments de la fonction :

- Une "scene" qui représente une scene en 3D
- Un "Graphics" qui dessine
- Une hauteur et une largeur "width" et "height"
- Une résolution , qui rendre plus ou moins précis la qualité de l'image
- BlockSize : qui définit la taille d'une zone de pixels
- start : qui affiche le temps d'execution

#### Description de la double boucle

La double boucle for dans la fonction renderScene() à parcourir chaque pixel de l'image (la premiere boucle pour la largeur et la deuxieme pour la hauteur).
uv rend des coordonnées normalisées, pour déterminer la direction du rayon
pixeldata renvoie les données du pixel comme la couleur ou autre
On set ensuite la couleur des pixel, et on dessine un rectangle aux coordonnées x y