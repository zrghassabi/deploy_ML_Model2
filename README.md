# deploy_ML_Model2-streamlit

https://streamlit.io/

https://www.analyticsvidhya.com/blog/2021/10/machine-learning-model-deployment-using-streamlit/

 https://towardsdatascience.com/how-to-deploy-machine-learning-models-601f8c13ff45
In general, there are different options to deploy ML models, such as Flask, Django, Streamlit, etc.
I will use Streamlit because it is the easiest and faster way to do it and it does not require any web development knowledge.

There are three main python files to build the application.

main.py, model.py, prediction.py


1- model.py — Build ML model and Save it.
2. prediction.py — Test saved ML model.
3. main.py — the main file to run the web app.


use WishWeightPredictionApplication in https://github.com/gurokeretcha/FishWeightPredictionApplication

Step 1: Create a new virtual environment using Pycharm IDE.

Step 2: Install necessary libraries. use requirements.txt

Step 3: Build the best machine learning model and Save it.

          model.py in this file, I created a machine learning model and saved it as a JSON file best_model.json.

          best_xgboost_model.save_model("best_model.json")

Step 4: Test the loaded model.

          prediction.py in this file, I test the loaded model and saved label-encoder classes as a classes.npy file using.

          np.save('classes.npy', label_encoder.classes_)

Step 5: Create main.py file

         Step 5.2: Load saved label encoder classes

         Step 5.3: Load saved the best model

         Step 5.4: Show dataframe on the web

         Step 5.5: Select Fish Species

         Step 5.6: Select each value of features using a slider window

         Step 5.7: Make prediction button

Step 6: Upload local project to Github

Step 7: Create an account on Streamlit

https://zrghassabi-deploy-ml-model2-main-18ujx1.streamlitapp.com/


