# singlestore_wine
Originally made for [SingleStore x Data Science UCSB x Coders SB Datathon](https://singlestore-ucsb-datathon-2024.devpost.com/). ([Our Submission](https://devpost.com/software/wine-quality-classifier))

Teammates: William Lee, Alexander Reyes, Mihir Srivistava, and me.

Instructions:

To run the SingleStore notebook, you don't need to download any files except the .ipynb. (The .csv files and .names are just for hosting the data here.)

Simply download the notebook from this repository and then open it in an editor that can open .ipynb notebooks. (This notebook was developed in SingleStore, so the dependencies are guaranteed to be properly installed if you open it there. To import into Singlestore: Singlestore -> Notebooks -> Dropdown Beside 'New Notebook' -> Import From File)

Make sure to run the cells in order (it takes some time). The last code cell creates interactive slider widgets that feed user input into the final model, so you can play with the classifier firsthand.

Sources:

[Red Wine Quality Dataset (required)](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
- added associated [White Wine Quality Dataset](https://archive.ics.uci.edu/dataset/186/wine+quality) from the same original paper

Besides documentations of the libraries used, all other technical information used is linked at the bottom of the notebook.

Libraries used: ipywidgets, scikit-learn, xgboost, pandas, matplotlib, seaborn, numpy
