# NLP_Text-Simplification
Here we provide a google colab ipynb notebook , consisting of our project code in its cell blocks

The goal of this project is to create an effective medical text simplification system that

we used Med-EASi dataset from hugging face , which can be import by :
dataset = load_dataset("cbasu/Med-EASi")
this is already implemented by a function - load_medeasi_dataset() with in the notebook

in later part of the code once the whole ipynb is run using different hugging face pretrained models :
- husseinMoh/t5-small 
- NourEldin/t5-small 
- esahit/t5-medical


use each model once while running the notebook the variable " model_name " needs to be updated to the specific pretrained model ,
which gives us the results 

if you need graphs for the results ( for each pretrained model )
after saving the fine tuned pretrained model give its path to the evaluation an you can get the graphs

