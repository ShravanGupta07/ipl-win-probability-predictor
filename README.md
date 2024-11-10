# IPL Win Predictor Web App
This project is an **IPL Win Predictor Web App** built using **Streamlit**, Python, and **Machine Learning**. The app predicts the probability of a team winning an IPL (Indian Premier League) cricket match based on various match conditions. The model is trained using historical IPL match data and provides win probabilities for both the batting and bowling teams.

## Features
**Team Selection**: Choose the batting and bowling teams from a list of IPL teams.
**City Selection**: Select the host city for the match from a list of IPL hosting cities.
**Target Score**: Enter the target score set by the opponent team.
**Current Score**: Input the current score of the batting team.
**Overs Completed**: Input the number of overs completed in the current innings.
**Wickets Out**: Input the number of wickets lost by the batting team.
The app uses a pre-trained machine learning model to predict the probability of winning based on the current match situation.

## Installation
To run this project locally, follow these steps:

### Prerequisites
Python 3.x
Streamlit
Pickle (for loading the pre-trained model)
### Steps
1. Clone the repository.
2. Ensure that the pipe.pkl file (pre-trained model) is in the project directory.
3. Run the Streamlit app:
4. streamlit run app.py
5. The app will be available in your browser at http://localhost:8501.

### Files
**app.py**: Main file for the Streamlit app that runs the IPL win prediction.
**pipe.pkl**: Pre-trained model used for predicting win probabilities based on match conditions.
### How it Works
**The user selects various match conditions (teams, city, target score, etc.) via a form.**
**The app processes these inputs and uses a machine learning model to predict the probability of each team winning.**
**The prediction is based on a pre-trained model stored in the pipe.pkl file, trained on historical IPL match data.**
