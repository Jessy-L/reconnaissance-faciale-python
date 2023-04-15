
# Reconnaissance faciale Python

Mettez à jour le dossier `known_faces` avec des images de personnes que vous voulez détecter et assurez-vous de couper autour des visages comme l'exemple de Zuckerberg (si vous ne le faites pas, l'exécution du programme peut lever une erreur).

Mettez seulement des fichiers d'images au format .jpg ou .png dans le dossier `known_faces`.

Pour exemple voir fichiers suivants:

```
/known_faces/Zuckerberg.png
/known_faces/YourPicture.jpg
```

Note le nom de reconnaissance affiché est pris à partir du nom du fichier (sans extension) qu'il correspond dans le dossier `known_faces`.

#### Camera

Vous devez avoir une caméra connectée à votre PC car le programme va afficher le flux vidéo de la caméra sur votre écran et va reconnaître les visages affichés s'ils font partie du dossier `known_faces`.

## Run

```
launch.py --i known_faces
```

## Windows

Pour Windows, installer les librairies suivantes:
- opencv-python
- CMake
- Visual Studio and the extension for C++ so that `dlib` installation completes successfully

Détection de visage par minimum norme entre vecteurs (128D dlib descriptor)


#### Outils nécessaires

- opencv
- dlib
- numpy
- imutils
- pillow

