
Nom du projet : # Image-Classification_Scanner
Il s'agit d'un projet de machine learning qui permet aux utilisateurs de classifier des images et d'extraire du texte à partir d'images sur un appareil Android en utilisant la bibliothèque TensorFlow Lite. Le projet a deux fonctionnalités principales : la classification d'images et la reconnaissance de texte.

Classification d'images
La fonctionnalité de classification d'images permet aux utilisateurs de classifier une image à l'aide d'un modèle pré-entraîné. L'application utilise le modèle Inception v3, qui est un réseau de neurones convolutifs entraîné sur l'ensemble de données ImageNet. L'utilisateur peut sélectionner une image à partir de la galerie de son appareil ou prendre une nouvelle photo à l'aide de l'appareil photo de son appareil. L'application classera ensuite l'image et affichera les cinq classes prédites les plus élevées ainsi que leurs probabilités correspondantes.

![A cat playing with a toy mouse](https://github.com/sanderseide/Image-Classification_Scanner/blob/master/20230320_205447.gif)

Reconnaissance de texte
La fonctionnalité de reconnaissance de texte permet aux utilisateurs d'extraire du texte à partir d'une image à l'aide de la reconnaissance optique de caractères (OCR). L'application utilise le moteur OCR Tesseract, qui est intégré à la bibliothèque TensorFlow Lite. L'utilisateur peut sélectionner une image à partir de la galerie de son appareil ou prendre une nouvelle photo à l'aide de l'appareil photo de son appareil. L'application extraira ensuite le texte de l'image et l'affichera à l'écran.

![A cat playing with a toy mouse](https://media.giphy.com/media/xT9DPyTQ5ZGj5c6fVu/giphy.gif)


Exigences
Android Studio 4.0 ou version ultérieure
Bibliothèque TensorFlow Lite
Modèle Inception v3
Moteur OCR Tesseract
Installation
Clonez le dépôt sur votre machine locale.
Ouvrez le projet dans Android Studio.
Compilez et exécutez l'application sur un appareil Android.
Utilisation
Ouvrez l'application sur votre appareil Android.
Pour classifier une image, sélectionnez l'option "Classification d'images" dans le menu principal.
Sélectionnez une image à partir de la galerie de votre appareil ou prenez une nouvelle photo à l'aide de l'appareil photo de votre appareil.
L'application classera l'image et affichera les quatre classes prédites qui sont Banana", "Orange", "Pen", "Sticky Notes" dans mon modele.

Pour extraire du texte à partir d'une image, sélectionnez l'option "Image to text" et pour la classification sélectionnez "take picture" dans le menu principal.
Sélectionnez une image à partir de la galerie de votre appareil ou prenez une nouvelle photo à l'aide de l'appareil photo de votre appareil.
L'application extraira le texte de l'image et l'affichera à l'écran.

Licence
Ce projet est sous licence MIT - voir le fichier LICENSE.md pour plus de détails.
