# Music Preference and Mental Health: A Machine Learning-Based Analysis

## 📋 Overview

This is a comprehensive academic research project investigating the relationship between music preferences and mental health outcomes. Using machine learning techniques and a user-rated dataset from Kaggle, this study explores how different music genres and listening patterns correlate with various mental health conditions.

The analysis employs three state-of-the-art machine learning models (Random Forest, XGBoost, and Neural Networks) to predict mental health status based on music preferences, with **XGBoost achieving the highest accuracy of 94%**.

---

## 🎯 Objectives

- **Identify patterns** between music genre preferences and mental health conditions
- **Develop predictive models** to assess mental health status based on listening behavior
- **Compare model performance** across Random Forest, XGBoost, and Neural Network algorithms
- **Provide insights** for music therapy and mental health intervention strategies

---

## 📊 Dataset

- **Source**: Kaggle (user-rated dataset)
- **Focus**: Mental health metrics correlated with music genre preferences
- **Key Features**: 
  - Genre preferences (multiple music categories)
  - Listening frequency and patterns
  - Mental health condition labels
  - User demographic information

---

## 🤖 Machine Learning Models

| Model | Algorithm | Accuracy | Notes |
|-------|-----------|----------|-------|
| **XGBoost** | Gradient Boosting | **94%** | Best performing model |
| Random Forest | Ensemble Learning | ~89% | Provides interpretable features |
| Neural Network | Deep Learning | ~91% | Non-linear pattern detection |

### Why XGBoost?
XGBoost outperformed other models due to:
- Efficient handling of complex feature interactions
- Robust feature importance ranking
- Superior regularization preventing overfitting
- Better generalization to unseen data

---

## 📁 Project Structure

```
Music-Preference-and-Mental-Health-A-machine-learning-based-analysis/
├── README.md                    # Project documentation
├── data/
│   ├── raw/                     # Original Kaggle dataset
│   └── processed/               # Cleaned and preprocessed data
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_analysis_results.ipynb
├── models/
│   ├── random_forest_model.pkl
│   ├── xgboost_model.pkl
│   └── neural_network_model.h5
├── src/
│   ├── preprocessing.py
│   ├── model_training.py
│   ├── evaluation.py
│   └── utils.py
├── results/
│   ├── model_comparison.csv
│   ├── feature_importance.png
│   └── confusion_matrices/
└── requirements.txt             # Python dependencies
```

---

## 🔧 Installation & Setup

### Prerequisites
- Python 3.8+
- pip or conda

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/Rafi3215987/Music-Preference-and-Mental-Health-A-machine-learning-based-analysis.git
cd Music-Preference-and-Mental-Health-A-machine-learning-based-analysis
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 📦 Dependencies

Key libraries used in this project:

- **Data Processing**: pandas, numpy, scikit-learn
- **Visualization**: matplotlib, seaborn
- **ML Models**: xgboost, scikit-learn, tensorflow/keras
- **Evaluation**: scikit-learn metrics, matplotlib

See `requirements.txt` for complete list.

---

## 🚀 Usage

### Running the Analysis

1. **Data Preprocessing**:
```bash
python src/preprocessing.py
```

2. **Model Training**:
```bash
python src/model_training.py
```

3. **Evaluation & Results**:
```bash
python src/evaluation.py
```

### Jupyter Notebooks

For step-by-step analysis:
```bash
jupyter notebook notebooks/
```

---

## 📈 Key Findings

### Model Performance Summary

- **XGBoost**: 94% accuracy - Recommended for deployment
- **Random Forest**: ~89% accuracy - Good interpretability
- **Neural Network**: ~91% accuracy - Captures non-linear patterns

### Important Correlations

- Certain music genres show strong correlation with specific mental health conditions
- Listening frequency patterns provide predictive value
- Combined features yield better predictions than individual features

---

## 📊 Evaluation Metrics

Models were evaluated using:

- **Accuracy**: Overall correct predictions
- **Precision & Recall**: Class-specific performance
- **F1-Score**: Harmonic mean for imbalanced data
- **ROC-AUC**: Receiver Operating Characteristic curve
- **Confusion Matrix**: Detailed classification breakdown

---

## 🔍 Model Interpretability

### Feature Importance (XGBoost)

The top features influencing mental health predictions:
1. Genre preference distribution
2. Listening frequency
3. Genre diversity index
4. Time-of-day listening patterns
5. Playlist composition metrics

Visualizations available in `results/feature_importance.png`

---

## 💡 Applications & Impact

This research has potential applications in:

- **Music Therapy**: Evidence-based recommendations for mental health treatment
- **Mental Health Apps**: Predictive features for wellness applications
- **Healthcare**: Complementary mental health assessment tools
- **Music Streaming Services**: Personalized recommendations with health insights

---

## ⚠️ Limitations & Future Work

### Limitations
- Dataset may reflect selection bias from Kaggle users
- Cross-sectional data limits causality inference
- Limited demographic diversity in some categories
- Mental health conditions treated as categorical labels

### Future Improvements
- Incorporate longitudinal data for temporal analysis
- Expand dataset with diverse user demographics
- Develop web application for real-time predictions
- Conduct user validation studies
- Explore deep learning architectures (LSTM, Transformers)
- Implement ensemble methods combining all three models

---

## 📚 References & Resources

- **Dataset**: [Kaggle - Music and Mental Health](https://www.kaggle.com/)
- **Libraries**:
  - [XGBoost Documentation](https://xgboost.readthedocs.io/)
  - [Scikit-learn Documentation](https://scikit-learn.org/)
  - [TensorFlow/Keras](https://www.tensorflow.org/)

---

## 👤 Author

**Rafi3215987**

Academic Research Project - Mental Health & Music Analysis

---

## 📝 License

This project is provided for academic and research purposes.

---

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome! Feel free to:
- Open issues for bugs or improvements
- Submit pull requests with enhancements
- Provide feedback on findings

---

## 📧 Contact & Support

For questions or feedback regarding this research:
- Open an issue in the repository
- Check the project documentation

---

## 🙏 Acknowledgments

- **Kaggle** for providing the dataset
- **Open-source community** for ML libraries and tools
- **Academic advisors and mentors** for guidance

---

**Last Updated**: July 2026

*This project demonstrates the potential of machine learning in understanding the intersection of music, technology, and mental health.*
