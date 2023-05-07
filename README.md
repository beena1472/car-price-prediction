# car-price-prediction
A Machine Learning Project that uses Random Forest Regressor model to predict used cars price based on some attributes such as kilometers driven, age, number of previous owners etc.

Steps:
Creating a new Conda env.
Training.
Execution
Testing of the Model.
Dataset

1. ## Creating a new Conda environment
Its always better to implement a project in a new environment as you can know the exact requirements needed for the project to run. When we create a new environmen, we are starting with no pre-installed packages or tools. So to create a new environment in anaconda prompt use the command : conda create -n carprice python=3.6

and now activate and switch to this environment using the command: `conda activate carprice`

2. Training
3. Move to the location where you have cloned this repo, and now open the jupyter notebook from this directory. now run every cell in the notebook.

After every cell is done running, we see a new file with ".pkl" extension has been created in the same src folder. This file contains our model. A web interface has been developed using flask and HTML and can be used for prediction.

3.Working of the Model on real-time user inputs
I recommend to install the following packages in the "carprice" environment

- "flask" package : `pip install flask` command.

- "jsonify" package : `pip install jsonify` command.

- "requests" package : `pip install requests` command.

- "numpy" package : `pip install numpy` command.

- "sklearn" package : `pip install sklearn` command

Run the app.py in the anaconda prompt using python3 app.py


4.Testing the model


5.Dataset
The data we have used in this project was downloaded from Kaggle. It was uploaded from Cardekho.com . The dataset consists of 301 rows and 9 columns with no null values. Column data consist of independent Features. The independent features contain both categorical and numeric values.

