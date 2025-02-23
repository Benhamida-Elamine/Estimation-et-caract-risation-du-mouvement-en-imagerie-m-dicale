# Estimation-et-caracterisation-du-mouvement-en-imagerie-medicale


## Description du Projet
Ce projet vise à traiter des images médicales, en particulier des images 2D de l'abdomen, en utilisant des techniques de traitement d'image et d'analyse de données. Le projet est implémenté en Python et utilise des bibliothèques telles que NumPy, Matplotlib, OpenCV, et SciPy pour le traitement des images et l'analyse des données.

## Structure du Projet
- **Projet_ISD_VF.ipynb** : Le notebook Jupyter contenant le code principal du projet.
- **Rapport_projet_image_VF.pdf** : Le rapport détaillé du projet.
- **abdomen2D.dat** : Les données brutes des images 2D de l'abdomen.
- **loaddat.py** : Script Python pour charger les données à partir du fichier `abdomen2D.dat`.

## Prérequis
Pour exécuter ce projet, vous aurez besoin des bibliothèques Python suivantes :
- NumPy
- Matplotlib
- OpenCV (cv2)
- SciPy
- imageio
- tqdm
- scikit-image
- scikit-learn

Installez-les avec la commande suivante :
```bash
pip install numpy matplotlib opencv-python scipy imageio tqdm scikit-image scikit-learn
```

## Utilisation
### Chargement des données
Utilisez le script `loaddat.py` pour charger les données à partir du fichier `abdomen2D.dat`. Ce script définit une fonction `loaddat` qui lit les données binaires et les convertit en un tableau NumPy.

### Exécution du notebook
Ouvrez le notebook `Projet_ISD_VF.ipynb` dans Jupyter Notebook ou JupyterLab. Exécutez les cellules dans l'ordre pour charger les données, appliquer les traitements d'image et visualiser les résultats.

### Consultation du rapport
Le rapport `Rapport_projet_image_VF.pdf` fournit une explication détaillée des méthodes utilisées, des résultats obtenus et des conclusions du projet.

## Fonctions Principales
Le notebook contient plusieurs fonctions pour le traitement des images, notamment :
- `gradient(u)` : Calcule le gradient d'une image.
- `div(p)` : Calcule la divergence d'un champ vectoriel.
- `laplacian(u)` : Calcule le laplacien d'une image.
- `MSE(u_truth, u_estim)` : Calcule l'erreur quadratique moyenne entre deux images.
- `PSNR(u_truth, u_estim)` : Calcule le rapport signal sur bruit (PSNR) entre deux images.
- `convolve(f, G)` : Applique une convolution 2D à une image avec un noyau donné.

## Données
Les données utilisées dans ce projet sont stockées dans le fichier `abdomen2D.dat`. Ce fichier contient des images 2D de l'abdomen au format binaire. Le script `loaddat.py` est utilisé pour charger ces données dans un format exploitable par Python.

## Résultats
Les résultats du traitement des images sont visualisés directement dans le notebook `Projet_ISD_VF.ipynb`. Le rapport `Rapport_projet_image_VF.pdf` fournit une analyse détaillée des résultats et des conclusions tirées de l'étude.
