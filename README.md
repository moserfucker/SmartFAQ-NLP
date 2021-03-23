# SmartFAQ-NLP
Création d'une smart FAQ à partir de données de Stackoverflow disponibles sur Kaggle.
https://www.kaggle.com/stackoverflow/pythonquestions

## Description des fichiers
Doc2Vec.inypnb est le fichier du model Word2Vec et FastText.  
     
RNN.ipynb est le fichier du model RNN      
      
le dossier GPT2 comprend 4 fichier .ipynb comprennant le model, l'entrainement et le test avec GPT2 
        
01.Import_data.ipynb est un fichier permettant d'intégrer les fichiers nécessaires sous deepnote (plateforme similaire à google colab)     
     
requirements.txt est le fichier qui indique ce qu'il faut installer pour pouvoir tout utiliser dans le projet.    

## Installation
Lors de la mise en place du projet, pensez à mettre les trois fichiers nécessaires (questions.csv, answers.csv, tags.csv) dans un dossier data. 
      
Pour le reste, attention a bien faire attention au chemin utilisé afin qu'il n'y est pas de soucis lors de l'utilisation des données pour les phases d'entrainement et de test.
