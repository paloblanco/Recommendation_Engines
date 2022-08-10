# Recommending articles to users with IBM

This project is used to develop several recommendation systems for users of IBM Watson Studio. The code develop here could be deployed to a full-stak application to enable article recomendations for users. This work has been completed as part of my Data Science Nanodegree with Udacity.

## Motivation

IBM has provided Udacity users with a dataset describing how about ~5000 users of the IBM Watson platform have interacted with about ~700 articles. Our goal is to develop several recomendation systems for users of this platform.

## Setup

You can just view the results of this activity by examining "Recommendations_with_IBM.html." The python notebook version, "Recommendations_with_IBM.ipynb," will render nicely in github for you.

If you want to be able to run "Recommendations_with_IBM.ipynb" yourself, do the following:

1. Clone this repo, then set up a virtual environment in the project root:

    ```cmd
    \\\Disaster_Response_App> python -m venv venv
    ```

2. Activate the virtual environment and install requirements with pip:

    ```cmd
    (venv) \\\Disaster_Response_App> python -m pip install -r requirements.txt
    ```

3. Start a Jupyter session and open "Recommendations_with_IBM.ipynb".

## Repo contents

"Recommendations_with_IBM.ipynb" contains the code used for this activity. In this notebook, we carry out the following activities:

1. Exploratory Data Analysis
2. Rank Based Recommendations
3. User-User Based Collaborative Filtering
4. Content Based Recommendations (EXTRA - NOT REQUIRED) - I may execute this later as time allows
5. Matrix Factorization
6. Extras & Concluding

You can explore this notebook and learn from the various modeling methods used.

Other important files in this repo:
- project_tests.py - unit tests that mus be passed
- top_5.p, top_10.p, top_20.p, user_item_matrix.p - pickle files provided by Udacity for comparing articles and intermediate results
- data:
    - articles_community.csv - list of article names, content, and ids from IBM Watson
    - user-item-interactions.csv - table describing a subset of user-article interactions on the IBM Watson platform.

## Acknowledgements
The template for this project has been provided by Udacity's "Data Scienctist Nanodegree Program."

Data have been provided to Udacity from [IBM](https://dataplatform.cloud.ibm.com/login).