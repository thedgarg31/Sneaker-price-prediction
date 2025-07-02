
# 🏷️ The Price Prediction of Sneakers Based on Machine Learning

A full-stack Django web application that predicts sneaker prices using machine learning. This project allows users and admins to upload sneaker data, visualize market trends, and predict prices with ease. Built with clean UI, robust backend, and real data from the StockX sneaker dataset.

## 🚀 Features

- 🔐 User Registration & Authentication
- 🧑‍💻 Separate Dashboards for Admin & Users
- 📊 Upload and Explore Sneaker Datasets (CSV)
- 📈 Visualize Trends by Model, Region, and Date
- 🤖 Price Prediction using Trained ML Models
- 💻 Responsive UI using Bootstrap and Modern CSS

## 🗂️ Project Structure

```

price prediction/
├── admins/                            # Admin-specific logic
│   ├── views.py, models.py, ...
├── users/                             # User management
│   ├── forms.py, models.py, ...
├── media/                             # Uploaded sneaker datasets (CSV)
├── static/                            # Static assets (CSS, JS, images)
├── templates/                         # HTML Templates
│   ├── AdminLogin.html, UserLogin.html, ...
├── ThePricePredictionOfsneakersBasedOnMachineLearning/
│   ├── settings.py, urls.py, views.py
├── db.sqlite3                         # Database
├── manage.py
└── requirements.txt

````

## 🛠️ Getting Started

### ✅ Prerequisites

- Python 3.8+
- pip (Python Package Installer)
- virtualenv *(recommended)*

### ⚙️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/sneaker-price-prediction.git
   cd sneaker-price-prediction/price\ prediction
````

2. **Set Up Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate        # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Database Migrations**

   ```bash
   python manage.py migrate
   ```

5. **Run Development Server**

   ```bash
   python manage.py runserver
   ```

6. **Visit the Application**
   Open your browser and go to:
   [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🧪 Usage

1. **Register** as a new user or **log in** as admin.
2. **Upload** sneaker datasets (.csv) from the dashboard.
3. **Explore trends** through interactive visualizations.
4. **Predict prices** for various sneaker models using ML.

---

## 🤝 Contributing

Pull requests and contributions are welcome!

1. Fork the repository
2. Create a feature branch
   `git checkout -b feature/YourFeature`
3. Commit your changes
   `git commit -m "Add Your Feature"`
4. Push to your fork
   `git push origin feature/YourFeature`
5. Submit a pull request 🎉

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

* [Django](https://www.djangoproject.com/)
* [Bootstrap](https://getbootstrap.com/)
* [StockX Sneaker Dataset (Kaggle)](https://www.kaggle.com/datasets/stockx/stockx-sneaker-data-2019)

---

## 📬 Contact

Made with ❤️ by [Sahithi Nandikula](https://github.com/sahithinandikula)
📫 For collaboration or questions, feel free to reach out!

```


