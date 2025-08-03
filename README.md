# 🌸 Iris Species Classification Project

This repository contains a re-implementation of a classic Iris classification project. The primary goal of this endeavor was to solidify my understanding of end-to-end machine learning workflows, from data handling to model deployment.

This project uses the famous Iris dataset, pioneered by Ronald Fisher in 1936, to build and deploy a machine learning model.


### 1. Iris setosa Sample
![Iris setosa species](https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Kosaciec_szczecinkowaty_Iris_setosa.jpg/320px-Kosaciec_szczecinkowaty_Iris_setosa.jpg)

### 2. Iris Feature Comparison
![Iris feature comparison chart](https://miro.medium.com/max/3500/1*f6KbPXwksAliMIsibFyGJw.png)

![Iris k-means clustering visualization](https://content.codecademy.com/programs/machine-learning/k-means/iris.svg)

## 🚀 Key Features

- **Classic Dataset**: 150 samples of 3 species (*setosa*, *versicolor*, *virginica*) with sepal/petal measurements
- **ML Pipeline**: 
  - Decision Tree classifier (`sklearn`)
  - Model evaluation (accuracy, classification report)
- **Modern Stack**:
  - Interactive UI with `Streamlit`
  - Cloud data integration via `Firestore`
- **Educational Focus**:
  - Full project lifecycle demonstration
  - Best practices in ML deployment


## 🎓 Learning Outcomes

Through rebuilding this classic ML project with modern tools, I've gained hands-on experience with:

<table>
  <tr>
    <td><strong>🧠 Core ML Concepts</strong></td>
    <td><strong>🛠️ Technical Skills</strong></td>
    <td><strong>🚀 Deployment Skills</strong></td>
  </tr>
  <tr>
    <td>
      • End-to-end project lifecycle<br>
      • Feature engineering<br>
      • Model evaluation metrics
    </td>
    <td>
      • Scikit-learn pipelines<br>
      • Streamlit UI development<br>
      • Firestore integration
    </td>
    <td>
      • Production-grade app design<br>
      • Environment configuration<br>
      • Dependency management
    </td>
  </tr>
</table>

### Key Takeaways:
- **Interpretability**: Learned to explain model decisions using feature importance and tree visualization
- **Reproducibility**: Implemented virtual environments and requirement freezing
- **Scalability**: Designed for cloud data integration from the start
- **User Experience**: Created intuitive interfaces for non-technical users

## 🖥️ Usage

1. Configure Firestore credentials in `config.py`  
2. Launch the app:  
```bash
streamlit run app/streamlit_app.py
```


## 🛠️ Installation

```bash
git clone https://github.com/mnDylan/iris-classification-project
cd iris-project
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
```



