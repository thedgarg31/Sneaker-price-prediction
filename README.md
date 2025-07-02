

```markdown
# 👟 The Price Prediction of Sneakers Based on Machine Learning

A full-stack Django web application that predicts sneaker prices using machine learning techniques. This platform allows users and admins to upload sneaker data, visualize pricing trends, and make intelligent price predictions based on historical data.



## 🔍 Project Overview

**Sneaker Price Prediction** is a Django-based web app that enables users to forecast sneaker prices using machine learning. With a focus on user-friendly data interaction, it provides visual insights into sneaker trends and pricing, while also allowing admins to manage uploaded datasets.

---

## ✨ Features

- 🔐 User registration & authentication (user/admin roles)
- 📂 Upload and manage sneaker datasets (CSV format)
- 📈 Visualize sneaker price trends by region, model, and date
- 🤖 Predict sneaker prices using trained ML models
- 📊 Interactive and responsive data dashboards
- 💻 Mobile-friendly interface with modern UI (Bootstrap-based)

---

## 🛠️ Tech Stack

| Layer         | Tools Used                           |
|---------------|---------------------------------------|
| Frontend      | HTML, CSS, Bootstrap 5                |
| Backend       | Python, Django                        |
| ML & Data     | Pandas, NumPy, Scikit-learn           |
| Database      | SQLite                                |
| Visualization | Matplotlib, Seaborn                   |
| Templates     | Django Templating Engine              |

---

## 📁 Project Structure

```

price prediction/
├── manage.py
├── db.sqlite3
├── requirements.txt
├── admins/                      # Admin views and models
├── users/                       # User forms, models, views
├── media/                       # Uploaded datasets
├── static/                      # CSS, JS, images
├── templates/                   # HTML files
│   ├── base.html
│   ├── AdminLogin.html
│   ├── UserLogin.html
│   └── ...
├── ThePricePredictionOfsneakersBasedOnMachineLearning/
│   ├── settings.py
│   ├── urls.py
│   └── views.py

````

---

## ⚙️ Installation

### 🔧 Prerequisites

- Python 3.8+
- pip
- virtualenv (recommended)

### 🔌 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/sneaker-price-prediction.git
   cd sneaker-price-prediction/price\ prediction
````

2. **Create a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**

   ```bash
   python manage.py migrate
   ```

5. **Run the server**

   ```bash
   python manage.py runserver
   ```

6. **Access the app**
   Open your browser and visit: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🚀 Usage

* Register or log in as a user/admin.
* Upload sneaker price datasets (in CSV format).
* Navigate to the dashboard to explore trends.
* Use the prediction interface to get estimated prices based on model, release date, and region.

---

## 📊 Machine Learning Model

* **Dataset**: [StockX Sneaker Data 2019 (Kaggle)](https://www.kaggle.com/datasets/stockx/stockx-sneaker-data-2019)
* **Model Used**: Linear Regression / Random Forest (based on training accuracy)
* **Libraries**: Scikit-learn, Pandas, NumPy
* **Target Variable**: `Sale Price`
* **Features**: `Brand`, `Model`, `Release Date`, `Retail Price`, `Condition`, `Region`

📁 Model training scripts are located in a separate Jupyter Notebook or `ml_model/` folder (if added).

---

## 📸 Screenshots

*Add relevant screenshots or GIFs here:*

* ✅ User Login Page
* ✅ Upload Dataset Page
* ✅ Prediction Form
* ✅ Graphs & Visualizations

> *(Tip: Add images in a `screenshots/` folder and embed them here using markdown.)*

---

## 🧑‍💻 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request ✅

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

* [Django](https://www.djangoproject.com/)
* [BootstrapMade Arsha Template](https://bootstrapmade.com/arsha-free-bootstrap-html-template-corporate/)
* [StockX Dataset - Kaggle](https://www.kaggle.com/datasets/stockx/stockx-sneaker-data-2019)
* [Scikit-learn](https://scikit-learn.org/)
* [Matplotlib](https://matplotlib.org/)

---

### 🔗 Connect with the Developer

**Sahithi Nandikula**
🌐 [GitHub](https://github.com/sahithinandikula)
📬 Open for collaborations and feedback!

```

