
---

## 🧑‍💻 **Real-Time Stock Price Prediction using Streamlit**

### 🚀 **Project Overview**

This project predicts stock prices using a **Linear Regression** model based on real-time stock price data fetched from the **Twelve Data API**. The user can input a stock symbol (e.g., `AAPL`), select the time interval, and see a live prediction of the stock's next price based on historical data.

### 🔧 **Tech Stack**

* **Python**: The core programming language.
* **Streamlit**: For building the interactive web application.
* **Twelve Data API**: To fetch real-time stock price data.
* **Scikit-learn**: For building the **Linear Regression** model.
* **Pandas & NumPy**: For data manipulation and analysis.
* **Matplotlib**: For data visualization.

### 🔑 **Features**

* Real-time stock price data fetching using the Twelve Data API.
* Linear Regression model to predict the next day's stock price.
* Visualization of **actual vs predicted prices** over time.
* Easy-to-use interface for entering stock symbols and selecting time intervals.

---

## 📜 **Getting Started**

### 1. **Clone this Repository**

Clone the repository to your local machine or use it in your preferred cloud platform like Streamlit Cloud or Heroku.

```bash
git clone https://github.com/your_username/real-time-stock-predictor.git
cd real-time-stock-predictor
```

### 2. **Install Dependencies**

Install the required Python dependencies using `pip`:

```bash
pip install -r requirements.txt
```

### 3. **Set Up Twelve Data API Key**

Sign up at [Twelve Data](https://twelvedata.com/) and get your free API key.

Once you have the key, update the `API_KEY` variable in the `app.py` file:

```python
API_KEY = 'your_api_key_here'
```

### 4. **Run the Streamlit App Locally**

Start the Streamlit app locally using the following command:

```bash
streamlit run app.py
```

You can access the app in your browser at `http://localhost:8501`.

### 5. **Deploy on Streamlit Community Cloud**

For a hosted version of the app:

1. Create a new repository on GitHub and push the files.
2. Sign in to [Streamlit Community Cloud](https://share.streamlit.io).
3. Click on "New App", link your GitHub repo, and deploy.

---

## 📊 **Usage**

1. Enter the **stock symbol** (e.g., `AAPL` for Apple).
2. Select the **interval** (e.g., 1-minute, 5-minute, or 15-minute).
3. Adjust the **number of data points** slider to specify how many points to fetch.
4. Click **"Fetch & Predict"** to see the predictions and visualization.

---

## 🎨 **Visualizations**

The app displays:

* A **line chart** comparing the **actual vs predicted stock prices**.
* The latest stock data fetched from the Twelve Data API.

---

## 📝 **Model Explanation**

The prediction model used in this app is **Linear Regression**, which takes historical closing prices as input and predicts the next price.

---

## 🔄 **Future Enhancements**

* Implementing **advanced models** like LSTM (Long Short-Term Memory) for better accuracy.
* Supporting **multiple stock symbols** for side-by-side comparison.
* Integrating **real-time updates** to refresh predictions without manual input.

---

## 💬 **Contributing**

Feel free to fork the repository and submit pull requests. If you find any bugs or want to add new features, feel free to open an issue.

---

## 📑 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

