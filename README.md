# Titanic_decision_tree_implementation
This repo is based upon the introduction and implementation of Decision Tree with the help of Titanic Dataset.

# Dependencies
    1. Python - Programming Language
    2. Flask - The framework used
    3. scikit-learn - machine learning framework
    4. Pip - Dependency Management

# Virtual environment 
    $ sudo apt-get install python-virtualenv
    $ python3 -m venv venv
    $ . venv/bin/activate
    $ pip install Flask

# Install all project dependencies using:
    $ pip install -r requirements.txt

# Running   
    $ export FLASK_APP=api.py
    $ export FLASK_ENV=development
    $ python -m flask run
    
    This launches a very simple builtin server, which is good enough for testing but probably not what you want to use in production.

    If you enable debug support the server will reload itself on code changes, and it will also provide you with a helpful debugger if things go wrong.

     If you have the debugger disabled or trust the users on your network, you can make the server publicly available simply by adding --host=0.0.0.0 to the command line:
      
      -- flask run --host=127.0.0.1:5000
 
 # running from prompt
    We can use and start the WSGI server using conda/python prompt using 
    
    $ python app.py 
    
    or 
    
    $ python manage.py runserver
      
## Contirbuing 
    This API was developed based on:
    
    1. Flask documentation
    
    2. REST APIs with Flask and Python
    
    3. Dataset - https://raw.githubusercontent.com/BigDataGal/Python-for-Data-Science/master/titanic-train.csv
  
## License
    This project is licensed under the MIT License - see the LICENSE.md file for details

## introduction :
    ### Problem:- to build an end-to-end Flask API for the Prediction of the proability of survival of people in titanic ship dataset.
    -- there are in total we have 11 different features present in the dataset but, after the analysis and all i have made the model with the help of only 6 different features and have gained training accuracy of 87% and testing accuracy of 82% approx..

## I have collected the dataset from URL.
   [[https://raw.githubusercontent.com/BigDataGal/Python-for-Data-Science/master/titanic-train.csv](https://raw.githubusercontent.com/BigDataGal/Python-for-Data-Science/master/titanic-train.csv)](https://raw.githubusercontent.com/BigDataGal/Python-for-Data-Science/master/titanic-train.csv)
    ### Preprocessing and visualize is taken place and tried to present a way for feature selection , cross validation, building confusion matrix.
          
## Machine Learning supervised model strategy 
   The project is built in the prospect to learn about Decision Tree, implemented the model and used hyper-parameter tuning K-fold in order to improve the accuracy.





