# TAXI-FAIR-PRICE

# NYC Taxi Fare Prediction 🚖

![NYC Taxi](https://images.openai.com/thumbnails/url/kxi9h3icu1mUUVJSUGylr5-al1xUWVCSmqJbkpRnoJdeXJJYkpmsl5yfq5-Zm5ieWmxfaAuUsXL0S7F0Tw5MS3TxNPE2LAsLsUytMk5PDDPO8TMsDnczSjUtsSjOqCg1DtH1LvfLD7eILMl0SXHMKKlIq9AtKPZVKwYAtpApSw)  
![NYC Taxi Street](https://images.openai.com/thumbnails/url/Sm2qS3icu1mSUVJSUGylr5-al1xUWVCSmqJbkpRnoJdeXJJYkpmsl5yfq5-Zm5ieWmxfaAuUsXL0S7F0Tw6KN3Q08HR1KjSoCDR0jAiodHEJtXBJdHVy8fXyDizNS_c2KIs09ygItcgsNg1PCquyDPU2MHXKCsuMTFcrBgDd7yh8)  
![NYC Taxi Night](https://images.openai.com/thumbnails/url/DG4LJ3icu1mUUVJSUGylr5-al1xUWVCSmqJbkpRnoJdeXJJYkpmsl5yfq5-Zm5ieWmxfaAuUsXL0S7F0Tw7K8ItMN41MjTAztUjXdQn3Mgl0i4hPz7Q0DIlPzkhODfPL8i-pSs_zDHQKrfCpKnYpD00u98gyMdNVKwYAssko9Q)  
![NYC Taxi in Rain](https://images.openai.com/thumbnails/url/4t74NHicu1mSUVJSUGylr5-al1xUWVCSmqJbkpRnoJdeXJJYkpmsl5yfq5-Zm5ieWmxfaAuUsXL0S7F0Tw7yyQj1TkutqiwMNKrwKw7N9TQ3qkx3ik8t0HUsCzat8vI0DAgrr9INN64ssihJNCkyLEsvjHQpiHDyL1crBgAwjypu)  

---

## 📌 Overview  
This project focuses on predicting the fare of NYC taxi rides based on historical trip data. It involves **data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning modeling** to create accurate fare prediction models.  

---

## 📂 Dataset  
We use the official NYC Yellow Taxi dataset available on Kaggle:  

🔗 [NYC Taxi Fare Prediction Dataset – Kaggle](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction)  

The dataset contains:  
- Pickup & drop-off coordinates  
- Date & time of the ride  
- Passenger count  
- Trip distance  
- Fare amount  

---

## 🗂 Project Structure  

```
├── data/
│   └── taxi_data.csv
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   └── model_training.ipynb
├── src/
│   ├── preprocess.py
│   ├── train_model.py
│   └── utils.py
├── README.md
└── requirements.txt
```

---

## 🔍 Key Features  
- **Data Cleaning**: Handle missing values, remove outliers, filter incorrect coordinates.  
- **EDA & Visualization**: Trip density maps, time-based patterns, distance vs fare analysis.  
- **Machine Learning**: Regression models like XGBoost, Random Forest, and Linear Regression.  
- **Interactive Predictions**: Streamlit or Flask app to input ride details & get fare predictions instantly.  

---

## 🚀 Installation  

```bash
git clone <your-repo-url>
cd nyc-taxi-fare
pip install -r requirements.txt
```

---

## ▶️ Usage  
1. Download dataset from Kaggle and place it in `data/` folder.  
2. Run preprocessing:  
   ```bash
   python src/preprocess.py
   ```  
3. Train the model:  
   ```bash
   python src/train_model.py
   ```  
4. Launch the app:  
   ```bash
   streamlit run app.py
   ```  

---

## 📸 Visuals  
The visuals below show NYC taxis in different settings — these help bring context to the dataset we’re working with:  

| ![Day Taxi](https://images.openai.com/thumbnails/url/kxi9h3icu1mUUVJSUGylr5-al1xUWVCSmqJbkpRnoJdeXJJYkpmsl5yfq5-Zm5ieWmxfaAuUsXL0S7F0Tw5MS3TxNPE2LAsLsUytMk5PDDPO8TMsDnczSjUtsSjOqCg1DtH1LvfLD7eILMl0SXHMKKlIq9AtKPZVKwYAtpApSw) | ![Street Taxi](https://images.openai.com/thumbnails/url/Sm2qS3icu1mSUVJSUGylr5-al1xUWVCSmqJbkpRnoJdeXJJYkpmsl5yfq5-Zm5ieWmxfaAuUsXL0S7F0Tw6KN3Q08HR1KjSoCDR0jAiodHEJtXBJdHVy8fXyDizNS_c2KIs09ygItcgsNg1PCquyDPU2MHXKCsuMTFcrBgDd7yh8) |  
|---|---|  
| ![Night Taxi](https://images.openai.com/thumbnails/url/DG4LJ3icu1mUUVJSUGylr5-al1xUWVCSmqJbkpRnoJdeXJJYkpmsl5yfq5-Zm5ieWmxfaAuUsXL0S7F0Tw7K8ItMN41MjTAztUjXdQn3Mgl0i4hPz7Q0DIlPzkhODfPL8i-pSs_zDHQKrfCpKnYpD00u98gyMdNVKwYAssko9Q) | ![Rain Taxi](https://images.openai.com/thumbnails/url/4t74NHicu1mSUVJSUGylr5-al1xUWVCSmqJbkpRnoJdeXJJYkpmsl5yfq5-Zm5ieWmxfaAuUsXL0S7F0Tw7yyQj1TkutqiwMNKrwKw7N9TQ3qkx3ik8t0HUsCzat8vI0DAgrr9INN64ssihJNCkyLEsvjHQpiHDyL1crBgAwjypu) |  

---

## 📜 License  
MIT License.  
