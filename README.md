# Cricket Win-Lose Probability Prediction

## Project Overview
The **Cricket Win-Lose Probability Prediction** project aims to predict the probability of a cricket team winning or losing based on real-time match data. Using machine learning models trained on IPL match datasets, the app provides an accurate and interactive way to forecast match outcomes. The app uses a Random Forest Classifier to analyze factors such as remaining runs, balls left, current run rate, and wickets in hand.

[Live Demo](https://cricket-win-lose-probability-prediction.streamlit.app/)

---

## Features
- **Predictive Analysis:** Provides the probability of a team's victory in a cricket match.
- **User-Friendly Interface:** Simple and intuitive design using Streamlit.
- **Real-Time Input:** Users can input match situations, such as scores, wickets, and overs, to get instant predictions.
- **Visual Insights:** Displays probabilities and match outcomes interactively.
- **Customizable Predictions:** Allows users to adjust match data inputs to observe outcomes under different scenarios.

---

## Business Objective
This project addresses the need for:
1. **Cricket Analytics:** Leveraging data to make informed predictions during cricket matches.
2. **Fan Engagement:** Enhancing the cricket-watching experience by providing real-time insights.
3. **Decision-Making Support:** Assisting analysts, teams, and fans in understanding match scenarios and predicting outcomes effectively.

---

## Accuracy and Importance
- The **Random Forest Classifier** achieves an **accuracy of 99.92%** based on historical IPL match data.
- The model's importance lies in its ability to handle categorical and numerical features effectively while minimizing overfitting.
![image](https://github.com/user-attachments/assets/0c491344-fe26-4277-b9af-bce5b44ac9c1)
![image](https://github.com/user-attachments/assets/2d78f423-89ee-4dd3-a85c-869595a71cb7)


---

## Future Objectives
1. Expand the dataset to include more recent matches and other cricket leagues.
2. Integrate live match data APIs for real-time predictions during matches.
3. Add advanced visualization features, such as predicted score graphs.
4. Incorporate more machine learning and deep learning models for comparison.
5. Enhance the app’s UI with additional analytical tools for match strategies.

---

## Outcome and Impact
- **Enhanced Fan Experience:** Offers cricket fans a fun and engaging way to predict match outcomes.
- **Decision Support:** Aids in analyzing match scenarios for broadcasters and sports analysts.
- **Practical Application:** Demonstrates the power of machine learning in sports analytics.

---

## How to Use the App
1. Visit the [Live Demo](https://cricket-win-lose-probability-prediction.streamlit.app/).
2. Select the **Batting Team**, **Bowling Team**, and **City** from the dropdown menus.
3. Input match details:
   - Runs Left
   - Balls Left
   - Wickets in Hand
   - Target Score
   - Current Run Rate (CRR)
   - Required Run Rate (RRR)
4. Click the **Predict Outcome** button to view:
   - Win Probability for the batting team
   - Lose Probability
5. Experiment with different inputs to simulate various match scenarios.

![image](https://github.com/user-attachments/assets/b1510a24-9e95-4ac2-945d-d6ea54e201bd)


---

## Technologies Used
- **Machine Learning:**
  - Scikit-learn
  - Random Forest Classifier
- **Data Visualization:**
  - Matplotlib
  - Seaborn
- **Web Framework:**
  - Streamlit
- **Programming Languages:**
  - Python
- **Data Preprocessing:**
  - Pandas
  - NumPy
- **Deployment:**
  - Streamlit Cloud


