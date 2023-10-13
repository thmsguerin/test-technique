# test-technique
Test technique pour un processus de recrutement.  
  
Il y avait 3 objectifs principaux :  
  &nbsp;&nbsp;&nbsp;1/ Cropping the WSI to get only the “tissue regions”.  
  &nbsp;&nbsp;&nbsp;2/ you should provide the “mask” needed as input for segmentation network  
  &nbsp;&nbsp;&nbsp;3/ This mask should fit into the following model, which should be completed and functional (ready to train on a large scale, if sufficient data are available)  
  
  
Voici un exemple de résultat obtenu :  
![Exemple de résultats](https://github.com/thmsguerin/test-technique/blob/main/results.png)   
  
  
Le fichier principal est un notebook Jupyter (test_diadeep.ipynb).     
L'environnement de travail conda utilisé a été exporté en un fichier 'test-diadeep.yml' disponible à la racine de ce repo.  
ATTENTION :  
l'image WSI fournie pour l'exercice ne peux pas être chargée sur Github, mais pour le bon déroulement du notebook elle doit être placée dans le dossier 'data', avec le fichier .csv des annotations. 
