# Movie Recommendation System using Restricted Boltzmann Machines (RBMs)

## 📌 Project Overview
This project implements a **Personalized Movie Recommendation System** using **Restricted Boltzmann Machines (RBMs)** on the **MovieLens dataset**, a widely used dataset containing user ratings for various movies. The system learns latent user and movie features to predict user preferences and generate personalized recommendations.

---

## 🚀 Features
- **Collaborative Filtering:** Recommends movies based on user behavior without needing explicit user profiles.
- **Latent Feature Extraction:** Learns hidden patterns in user-movie interactions to represent user preferences and movie characteristics.
- **Contrastive Divergence Optimization:** Ensures faster and more stable training for RBMs.
- **Handles Sparse Data:** Efficiently works with incomplete or sparse rating datasets.

---

## 🔧 Tech Stack
- **Python**
- **TensorFlow/Keras**
- **NumPy, Pandas**
- **Matplotlib (optional for visualization)**

---

## 📂 Dataset
- **MovieLens dataset** (https://grouplens.org/datasets/movielens/)
- Includes user ratings for thousands of movies, commonly used for building recommendation systems.

---

## 🛠️ Setup & Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/movie-recommender-rbm.git
   cd movie-recommender-rbm
   ```
2. **Install required libraries:**
   ```bash
   pip install tensorflow numpy pandas matplotlib
   ```
3. **Download the dataset:**
   ```bash
   wget -O movielens.zip "https://grouplens.org/datasets/movielens/"
   unzip movielens.zip
   ```

---

## 🧠 Model Architecture
The system consists of:
- **Visible Layer:** Represents user-movie interactions (ratings).
- **Hidden Layer:** Captures latent user preferences and movie features.
- **Weight Matrix:** Connects visible and hidden layers, optimized through Contrastive Divergence.

---

## 🔥 Training Process
1. **Preprocess** the dataset — normalize and prepare data.
2. **Train the RBM** using Contrastive Divergence to learn latent features.
3. **Generate recommendations** by reconstructing user preferences from the hidden layer.

---

## 🎯 Results
- Extracted meaningful latent representations from user-movie interactions.
- Delivered accurate, personalized recommendations based on learned user behavior.
- Handled sparse data effectively without overfitting.

---

## 📌 Future Enhancements
- Add evaluation metrics like **RMSE** or **Precision/Recall**.
- Implement hybrid recommendations by combining RBMs with **content-based filtering**.
- Extend support to larger datasets.

---

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📜 License
This project is licensed under the **MIT License** — feel free to use, modify, and distribute. ✨

Happy coding! 🚀

