# 🏏 IPL Match Win Predictor

A machine learning project that predicts the outcome of Indian Premier League (IPL) matches based on historical match data. This project uses team statistics, match context, and venue details to predict the winning team of an IPL match.

## 🎯 Objective

To build a predictive model that takes match-related features as input and predicts which team is likely to win an IPL match.

## 🛠 Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn (Random Forest, Logistic Regression)
- Streamlit (for web deployment)
- Matplotlib, Seaborn (for visualization)
- Jupyter Notebook

## 📁 Project Structure

IPL-Win-Predictor/
├── data/
│ └── IPL_matches.csv
├── IPL_Win_Predictor.ipynb # Jupyter Notebook for analysis and model building
├── predictor_model.pkl # Trained machine learning model
├── app.py # Streamlit web app
├── README.md # Project documentation



## 🔄 Workflow

1. **Data Collection & Cleaning**
   - Loaded IPL match data from Kaggle
   - Cleaned null values and removed unnecessary columns

2. **Feature Engineering**
   - Selected relevant features such as team names, venue, toss winner, toss decision, etc.
   - Encoded categorical features using Label Encoding or One-Hot Encoding

3. **Model Building**
   - Trained a Random Forest Classifier to predict match outcomes
   - Evaluated model using accuracy score, confusion matrix

4. **Deployment**
   - Developed an interactive web app using Streamlit to allow users to input match conditions and get predictions

## 📊 Sample Input (via UI)

- Team 1: Chennai Super Kings
- Team 2: Mumbai Indians
- Toss Winner: CSK
- Toss Decision: Bat
- Venue: Wankhede Stadium

### ➡️ Output:
> Predicted Winner: **Chennai Super Kings**

## 🚀 Future Enhancements

- Add player-level performance data
- Use ensemble models or neural networks
- Incorporate live score updates for real-time predictions

## 📄 License

This project is licensed under the MIT License.

---

