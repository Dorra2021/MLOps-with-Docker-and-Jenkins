# MLOps-with-Docker-and-Jenkins

The purpose of this repository is to provide an example of how we can use DevOps tools like Docker and Jenkins to aumomate a Machine Learning Pipeline.
I will create a pipeline that automatically process raw data (données brutes), train model and return test accuracy every time we make a change in our repository.


adult.csv (input) ==> preprocessing-mlops-docker-jenkins.ipynb ==> train.csv / test.csv (output)

train.csv (input) ==> train.ipynb ==> model.joblib / train_metadata.json 





PS: cross valisation: 
C'est une méthode qui permet de tester les performances d'un modèle prédictif de ML. C'est une méthode de rééchantillonnage qui permet d'évaluer un modèle meme avec des données limitées.
Pour effectuer le VC, une partie de l'ensemble des données d'entrainnement est mise à coté à l'avance. Ces données ne seront pas utilisées pour entrainer le modèle, mais seront utilisées ultérieurement pour tester et valider le modèle.
