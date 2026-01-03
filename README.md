# 🎮 Indie Game Success Predictor

**Machine Learning system to predict indie game success, optimize launch strategy, and prioritize post-release development.**

## 📊 Project Overview

This project analyzes 90,000+ Steam games to help indie developers make data-driven decisions across three critical stages:

1. **Pre-Launch Predictor**: Validate game concept viability before development
2. **Launch Success Predictor**: Forecast long-term success from early signals (Coming Soon)
3. **Post-Launch Maintenance Advisor**: Prioritize bug fixes and features based on review sentiment (Coming Soon)

## 🎯 Business Problem

In 2024, 18,000 games launched on Steam, but only 32% generated more than $500 in revenue. This system helps indie developers:

- Identify profitable genres and market opportunities
- Optimize pricing strategy
- Choose optimal launch timing
- Reduce risk of market saturation

## 📁 Project Structure

```
indie-game-success-predictor/
│
├── data/
│   ├── raw/              # Original datasets (not tracked in Git)
│   ├── processed/        # Cleaned data ready for modeling
│   └── external/         # External data sources
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_modeling.ipynb
│
├── src/
│   ├── data/             # Data loading and preprocessing scripts
│   ├── features/         # Feature engineering scripts
│   ├── models/           # Model training and evaluation
│   └── visualization/    # Plotting functions
│
├── reports/
│   └── figures/          # Generated graphics and charts
│
├── requirements.txt      # Python dependencies
└── README.md
```

## 🛠️ Tech Stack

- **Python 3.10+**
- **Pandas & NumPy**: Data manipulation
- **Scikit-learn**: Machine Learning models
- **XGBoost**: Gradient boosting
- **Matplotlib & Seaborn**: Data visualization
- **NLTK**: Natural Language Processing (future phases)

## 📊 Dataset

**Source**: [Steam Games Dataset 2025](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset) (Kaggle)

- **Size**: 90,000+ games
- **Updated**: March 2025
- **Features**: 186 columns including genres, prices, reviews, tags, release dates

## 🚀 Getting Started

### Installation

1. Clone the repository:

```bash
git clone https://github.com/nnvelez95/indie-game-success-predictor.git
cd indie-game-success-predictor
```

2. Create virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Download dataset from Kaggle and place in `data/raw/`

## 📈 Current Status

**Phase 1: Data Exploration & Cleaning** - In Progress ⏳

- ✅ Project setup
- ✅ Exploratory Data Analysis (EDA)
- 🔄 Data cleaning and preprocessing
- ⏳ Feature engineering
- ⏳ Baseline model training

## 🎯 Roadmap

- **Week 1-2**: Core predictor (genre + price → sales)
- **Week 3-4**: NLP analysis (descriptions and reviews)
- **Week 5-6**: Computer Vision (cover art analysis)
- **Future**: Web dashboard for interactive predictions

## 👤 Author

**Nicolas Velez**

- GitHub: [@nnvelez95](https://github.com/nnvelez95)
- LinkedIn: [Tu perfil LinkedIn]

## 📝 License

MIT License - see LICENSE file for details

## 🙏 Acknowledgments

- Dataset by [artermiloff](https://www.kaggle.com/artermiloff) on Kaggle
- Inspired by the indie game development community

---

⭐ If you find this project useful, please consider giving it a star!
