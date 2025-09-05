📩 SMS Spam Detection
🔎 Overview

SMS Spam Detection is a machine learning project that takes an SMS as input and predicts whether the message is 📬 Spam or ✅ Not Spam.
The model is built with Python and deployed on the web using Streamlit for easy interaction.

🛠️ Technology Stack

  🐍 Python

  📊 Pandas & NumPy

  🤖 Scikit-learn

  🌐 Streamlit

✨ Features

  📥 Data collection

  🧹 Data cleaning & preprocessing

  📊 Exploratory Data Analysis (EDA)

  🧠 Model building & selection

  🚀 Web deployment with Streamlit

📥 Data Collection

  The dataset used is the SMS Spam Collection from Kaggle, consisting of 5,500+ SMS messages labeled as spam or ham (not spam).
📌 Dataset Link

🧹 Data Cleaning & Preprocessing

  Removed null & duplicate values

  Encoded labels (spam = 1, ham = 0)

Preprocessed text:

  🔡 Converted to lowercase

  ✂️ Removed special characters, punctuation & stopwords

  🌱 Applied stemming

📊 Exploratory Data Analysis (EDA)

  📏 Measured character, word & sentence counts

  🔗 Checked correlations between variables

  📈 Visualized using bar charts, pie charts, heatmaps & boxplots

  ☁️ Created word clouds for spam vs non-spam messages

  📝 Analyzed most frequent spam keywords

🧠 Model Building & Selection

  Tried multiple ML models:

  ✅ Naive Bayes

  🌲 Random Forest

  🌐 Logistic Regression

  🧩 Decision Tree

  📦 ExtraTreesClassifier

  🔍 KNN & SVC

📌 The best classifier achieved 100% precision on spam detection. 🚀

  🌐 Web Deployment

Built an interactive Streamlit Web App

User enters a message → model predicts spam/ham instantly

Simple and user-friendly interface

👉 Try the live demo here: SMS Spam Detection Web App

🖥️ Local Setup & Usage

Clone the repository

    git clone https://github.com/your-username/sms-spam-detection.git
    cd sms-spam-detection


Install dependencies

    pip install -r requirements.txt


Run the app

    streamlit run app.py


Open in browser:

    http://localhost:8501

🤝 Contributions

Contributions are welcome! 🎉

💡 Found a bug? Open an issue

🛠️ Want to improve the model or UI? Create a pull request
