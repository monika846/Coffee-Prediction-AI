☕ Coffee Prediction AI

A fun and interactive machine learning project that predicts a person’s coffee choice based on their mood, time of day, weather, and day of the week using a Random Forest Classifier.

🔗 Live App: Coffee Prediction App

📖 Blog: Read on Medium

🧠 Overview

This project showcases a beginner-friendly application of machine learning to predict coffee preferences. Built using Python and Streamlit, it accepts user inputs like mood, day, weather, and time — and returns a predicted coffee choice such as Latte, Espresso, or Cappuccino.

It also displays:

Model confidence

Useful visual insights

📽️ Demo

🔗 Try Live App

Simply input your:

Mood

Day of the week

Weather

Time of day

…and see what coffee your AI barista suggests! ☕

✨ Features

Simple and fun user interface (built with Streamlit)

Decision Tree-based prediction with Random Forest

Visualization of feature importance

Confidence score display

Clean and beginner-friendly codebase

📊 Dataset Schema

The dataset was manually created and consists of the following columns:

Column Name	Type	Description
day	string	Day of the week (e.g., Monday)
weather	string	Weather condition (e.g., Sunny)
time_of_day	string	Morning or Afternoon
mood	string	User mood (e.g., Happy, Tired)
coffee_choice	string	Target label (e.g., Latte, Espresso)
🛠️ Installation

Clone the repository:

git clone https://github.com/your-username/coffee-predictor.git
cd coffee-predictor


Create and activate a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate


Install the dependencies:

pip install -r requirements.txt

▶️ Usage

To run the app locally:

streamlit run smallcoffee.py


Then open the provided URL in your browser to interact with the app.

🧰 Technologies Used

Python – core programming language

Pandas – data handling

Scikit-learn – ML model (Random Forest Classifier)

Streamlit – web interface

Matplotlib / Seaborn – optional for visualizations

📁 Folder Structure
coffee-predictor/
├── coffee_predictor_app.py       # Main Streamlit app
├── data/                         # (Optional) Folder for data storage
├── requirements.txt              # Python dependencies
├── README.md                     # Project overview

👤 Author

Monika Wadhwani
