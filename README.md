# Adalovelace_day_Hackathon

Generate-Sonnets
Using a character-level language model to generate sonnets. We trained on a given dataset.txt sonnets and with files to make generating new sonnets easy for users.
File Descriptions
• Model.ipynb: Colab notebook including data loading and visualization, model training, and explaining the approach used and results.
• model.h5: Keras model trained on dataset1. This model is originally created, trained, and saved in the Model.ipynb notebook.
• sonnets.txt: A text file containing all of the sonnets where each sonnet is separated by two newline characters.
Requirements
• Python (3.x)
• Numpy (1.12.1 and up)
• Keras (2.1.4 and up)
• Tensorflow (1.5.0 and up)
Usage
The file Generate_sonnet.py loads the Keras model trained in Model.ipynb and automatically chooses a random seed text and generates characters (average sonnet length) that will print out to your console. To use it simply navigate to the directory where the python file is located and run the following command.
A newly generated sonnet will then print out to your console. You may get a warning message from TensorFlow about CPU instructions but you can ignore that.
Colab Environment
To activate the environment:
• Google Colab Notebook which comes with the preinstalled libraries.
