# 🎬 Movie Recommender System

A sophisticated movie recommendation engine built using **Item-Based Collaborative Filtering** on the MovieLens 100k dataset. This project demonstrates machine learning techniques for building personalized recommendation systems.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![Numpy](https://img.shields.io/badge/NumPy-Scientific%20Computing-orange.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 🎯 Project Overview

This project implements a collaborative filtering recommendation system that suggests movies to users based on similar user preferences and movie correlations. The system analyzes user rating patterns to identify movies that users with similar tastes have enjoyed.

### ✨ Key Features

- **Item-Based Collaborative Filtering**: Recommends movies based on item-to-item similarities
- **Data Visualization**: Comprehensive analysis of rating patterns and distributions
- **Correlation Analysis**: Mathematical approach to find movie similarities
- **Scalable Architecture**: Works with the entire MovieLens dataset
- **Custom Testing**: Ability to test with personal movie ratings

## 📊 Dataset

The project uses the **MovieLens 100k** dataset, which contains:
- 📈 **100,000 ratings** (1-5 stars)
- 👥 **943 users** 
- 🎥 **1,682 movies**
- 📅 Ratings from **1998**

**Source**: [GroupLens Research](https://grouplens.org/datasets/movielens/100k/)

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment


## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mehardeep79/Movie-Recommender-System.git
   cd movie-recommender-system
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Movie_Recommender_System.ipynb
   ```

## 🔍 How It Works

### 1. **Data Preprocessing**
- Import and merge movie titles with user ratings
- Clean data by removing unnecessary columns
- Create comprehensive movie-rating dataset

### 2. **Exploratory Data Analysis**
- Analyze rating distributions and patterns
- Identify popular and highly-rated movies
- Visualize data insights with charts and graphs

### 3. **Collaborative Filtering**
- Build user-movie rating matrix
- Calculate movie-to-movie correlations using Pearson correlation
- Generate recommendations based on similarity scores

### 4. **Recommendation Generation**
- Find movies similar to user preferences
- Weight recommendations based on correlation strength
- Return top N movie suggestions

## 📈 Key Results

The recommender system successfully identifies movie similarities with high accuracy:

### Example: Movies Similar to "Star Wars (1977)"
1. **Empire Strikes Back, The (1980)** - 0.748 correlation
2. **Return of the Jedi (1983)** - 0.673 correlation  
3. **Raiders of the Lost Ark (1981)** - 0.536 correlation
4. **Indiana Jones and the Last Crusade (1989)** - 0.350 correlation



## 🧪 Testing the System

You can test the recommender with your own movie preferences:

1. Edit `My_Ratings.csv` with your movie ratings
2. Run the recommendation algorithm
3. Get personalized movie suggestions



## 🔮 Future Enhancements

- Implement Matrix Factorization techniques
- Add Content-Based Filtering
- Integrate Deep Learning approaches
- Build a web interface for user interaction
- Add real-time recommendation updates
- Implement hybrid recommendation systems

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## ⭐ Show Your Support

Give a ⭐️ if this project helped you learn about recommendation systems!

