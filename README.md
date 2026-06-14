# ML-52-5930: Machine Learning Course Projects & Exercises

A comprehensive collection of machine learning projects and exercises covering fundamental to advanced ML algorithms, featuring interactive Jupyter Notebook implementations and a production-ready C++ TensorFlow Lite model for MNIST digit recognition.

## 📋 Overview

This repository showcases practical implementations of core machine learning techniques developed during the ML-52-5930 course. The projects demonstrate real-world applications of supervised learning, unsupervised learning, and deep learning methodologies.

## 🎯 Projects & Exercises

### Core Machine Learning Projects

1. **Clustering Project** (`Clustering Project.ipynb`)
   - Comprehensive unsupervised learning implementation
   - Multiple clustering algorithms and techniques
   - Data visualization and cluster analysis
   - Real-world dataset applications

2. **Classification Tasks** (`classification3.ipynb`)
   - Multi-class classification implementation
   - Advanced classification algorithms
   - Model evaluation and performance metrics
   - Feature engineering and preprocessing

3. **Logistic Regression** (`Exercise5_Logistic_Regression.ipynb`)
   - Binary classification fundamentals
   - Sigmoid activation and decision boundaries
   - Model interpretation and probability predictions
   - ROC curves and AUC analysis

### Specialized Algorithms

4. **K-Nearest Neighbors (KNN)** (`KNN Exercise.ipynb`)
   - Distance-based classification
   - Hyperparameter tuning (k-value optimization)
   - Performance analysis and visualization

5. **Regression Tasks** (`Regression Task.ipynb`)
   - Linear and non-linear regression
   - Prediction modeling
   - Error metrics and model evaluation

### Advanced Topics

6. **Clustering Exercises** (`Clustering Exercise.ipynb`)
   - K-means, hierarchical clustering
   - Dimensionality reduction techniques
   - Centroid analysis and optimization

7. **Lab 7 & Exercise 10** (`lab7.ipynb`, `Exercise10.ipynb`)
   - Advanced ML concepts
   - Real-world problem solving
   - Integration of multiple techniques

### Production Implementation

8. **MNIST Model (C++)** (`model.cc`, `model.h`)
   - TensorFlow Lite MNIST digit recognition model
   - Optimized C++ implementation
   - Binary model format for embedded systems
   - High-performance inference

## 🛠️ Technologies & Libraries

### Python (Jupyter Notebooks - 98.3%)
- **NumPy** - Numerical computing and array operations
- **Pandas** - Data manipulation and analysis
- **Scikit-learn** - Machine learning algorithms and preprocessing
- **Matplotlib & Seaborn** - Data visualization
- **TensorFlow/Keras** - Deep learning (where applicable)
- **SciPy** - Scientific computing

### C++ (Production Model - 1.7%)
- **TensorFlow Lite** - Lightweight ML inference engine
- **Standard C++ Libraries** - Core functionality

## 🚀 Quick Start

### Prerequisites
```
- Python 3.7+
- Jupyter Notebook or JupyterLab
- pip or conda package manager
- C++11 compiler (for model compilation)
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/darwish012/ML-52-5930.git
   cd ML-52-5930
   ```

2. **Set up Python environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn jupyter tensorflow
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

## 📊 Project Structure

```
ML-52-5930/
├── Clustering Project.ipynb          # Main clustering implementation
├── classification3.ipynb             # Classification project
├── Exercise5_Logistic_Regression.ipynb
├── KNN Exercise.ipynb
├── Regression Task.ipynb
├── Clustering Exercise.ipynb
├── lab7.ipynb
├── Exercise10.ipynb
├── model.cc                          # TensorFlow Lite C++ model
├── model.h                           # Model header file
└── README.md
```

## 🎓 Learning Outcomes

Through these projects, I've gained proficiency in:

- ✅ **Supervised Learning**: Classification and regression techniques
- ✅ **Unsupervised Learning**: Clustering and dimensionality reduction
- ✅ **Algorithm Implementation**: From scratch implementations and library usage
- ✅ **Data Preprocessing**: Cleaning, normalization, and feature engineering
- ✅ **Model Evaluation**: Metrics, validation strategies, and performance analysis
- ✅ **Production Deployment**: Converting models to optimized C++ for inference
- ✅ **Data Visualization**: Communicating insights effectively

## 💡 Key Highlights

### Machine Learning Algorithms Implemented
- K-Means Clustering
- Hierarchical Clustering
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Linear & Non-Linear Regression
- Multi-class Classification
- Neural Network models with TensorFlow Lite

### Datasets & Applications
- MNIST dataset (digit recognition)
- Real-world classification datasets
- Synthetic clustering datasets
- Regression problem datasets

## 📈 Model Performance

Each project includes:
- Comprehensive evaluation metrics
- Cross-validation results
- Performance comparisons
- Visualized results and insights
- Error analysis and interpretability

## 🔧 Usage Examples

### Running a Notebook
1. Open Jupyter: `jupyter notebook`
2. Navigate to the desired `.ipynb` file
3. Run cells sequentially to see algorithm execution
4. Modify hyperparameters and observe results

### Using the C++ Model
```cpp
#include "model.h"
// Use the MNIST model for inference
// Compile with TensorFlow Lite libraries
```

## 📚 Additional Resources

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [TensorFlow Lite Guide](https://www.tensorflow.org/lite)
- [Pandas Documentation](https://pandas.pydata.org/)
- [NumPy Reference](https://numpy.org/doc/stable/)

## 🤝 Contributing

This is a course project repository. For improvements, suggestions, or corrections, feel free to open an issue or pull request.

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Darwish** - ML-52-5930 Course Projects  
GitHub: [@darwish012](https://github.com/darwish012)

---

**Last Updated**: June 2026  
**Course Code**: ML-52-5930

