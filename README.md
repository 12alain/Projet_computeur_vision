## Projet_computeur_vision

## Description du projet
Ce projet consiste en une application web de classification de tumeurs cérébrales à l'aide d'images médicales.
L'application permet aux utilisateurs de télécharger des images médicales du cerveau et de prédire si une tumeur cérébrale est présente ou non.

 ## Dépendances
Pour exécuter le code et reproduire les résultats, vous aurez besoin des dépendances suivantes :
- Python 3.9+
- Jupyter Notebook ou Google Colab
- NumPy
- Pandas
- Matplotlib
- TensorFlow ou PyTorch
- Scikit-Learn
- OpenCV
- Autres bibliothèques selon les besoins (les exigences peuvent être trouvées dans le fichier d'environnement du projet)


## Données
Les données utilisées pour former le modèle proviennent du jeu de données suivant :

- Jeu de données : [https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/download?datasetVersionNumber=1]
- Nous effectuons des transformations necessaire sur nos donnees pour avoir des resultats satisfaisants .
- Le fichier data_tumeur.py permet de recuperer convenanblement les donnees depuis le dossier brain_tumor_dataset pour les chargees dans le model.

## Modèle
Un modèle de classification de tumeurs cérébrales a été utilisé pour classer les images médicales en deux catégories : "Présence de tumeur" et "Pas de tumeur".
Le modèle a été formé à l'aide de données provenant du jeu de données brain_tumor_dataset et en suivant les étapes décrites dans https://www.kaggle.com/code/harmandeepsinghpadam/pytorch-brain-tumor-classification-testacc-95. Le modèle formé est disponible dans le fichier model.py du projet et vous verrez dans le dossier model enregistrer .

## Fichier Important
Le fichier main.py permet d'entrainer le modele et de visualiser les courbes d'entrainement et de perte.
Le fichier utils.py permet de deployer notre application sur streamlit.

## Techniques de Data Augmentation
Pour améliorer la performance du modèle sur l'ensemble de données limité, certaines techniques d'augmentation de données peuvent être appliquées, telles que :
- Rotation et retournement d'image.
- Zoom et recadrage.
- Changement de contraste et de luminosité.
- Ajout de bruit artificiel, etc.

## Comment utiliser l'application
Pour utiliser l'application de classification de tumeurs cérébrales, suivez ces étapes :
1. Accédez à l'application en suivant le lien fourni.
2. Téléchargez une image médicale du cerveau depuis ce lien https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/download?datasetVersionNumber=1 ou sur le net pour tester le modele
3. Cliquez sur le bouton "Predict" pour obtenir la prédiction.
4. La prédiction sera affichée avec des informations sur la probabilité de présence de tumeur.

## Remarques
Assurez-vous que les images téléchargées sont de haute qualité et bien orientées pour des résultats précis.
Les résultats de la prédiction sont fournis à titre informatif uniquement.
Consultez un professionnel de la santé pour un diagnostic médical précis.

## License: 
Apache Version 2.0

## Authors
-Jean Marius	IBARA KIEBE KANIMBOET
-KADIDIA	KAREMBE
-Koudouregma Alain	KIEMDE
-Adamoh Franck	Kouassi
-OUMAR	KRA


# Projet de Classification de Tumeurs Cérébrales

Ce projet consiste en une application web de classification de tumeurs cérébrales à l'aide d'images médicales. L'application permet aux utilisateurs de télécharger des images médicales du cerveau et de prédire si une tumeur cérébrale est présente ou non.

## Données

Les données utilisées pour former le modèle proviennent du jeu de données suivant :

- Jeu de données : [https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/download?datasetVersionNumber=1]
- Nous effectuons des transformations necessaire sur nos  donnees pour avoir des resultat satisfesant .
- Le fichier data_tumeur.py permet de recuperer convenanblement les donnees depuis le dossier brain_tumor_dataset pour les chargees dans le model.

## Modèle

Un modèle de classification de tumeurs cérébrales a été utilisé pour classer les images médicales en deux catégories : "Présence de tumeur" et "Pas de tumeur".

Le modèle a été formé à l'aide de données provenant du jeu de données brain_tumor_dataset et en suivant les étapes décrites dans https://www.kaggle.com/code/harmandeepsinghpadam/pytorch-brain-tumor-classification-testacc-95.Le modèle formé est disponible dans le fichier model.py du  projet et vous verrez dans le dossier model le model enregistrer .

## Fichier Important
- le fichier main.py permet d'entrainer le modele et de visualiser les courbes d'entrainement et de perte 
- le fichier utils.py permet de deployer notre application sur streamlit .

## Comment utiliser l'application

Pour utiliser l'application de classification de tumeurs cérébrales, suivez ces étapes :

1. Accédez à l'application en suivant le lien fourni.
2. Téléchargez une image médicale du cerveau depuis ce lien https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/download?datasetVersionNumber=1 ou sur le net pour tester le modele 
3. Cliquez sur le bouton "Predict" pour obtenir la prédiction.
4. La prédiction sera affichée avec des informations sur la probabilité de présence de tumeur.

## Remarques

- Assurez-vous que les images téléchargées sont de haute qualité et bien orientées pour des résultats précis.
- Les résultats de la prédiction sont fournis à titre informatif uniquement. Consultez un professionnel de la santé pour  un diagnostic médical précis.

