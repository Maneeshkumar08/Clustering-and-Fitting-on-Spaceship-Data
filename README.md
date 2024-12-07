### Clustering and Fitting on Spaceship Titanic Data

This repository contains the implementation of clustering and supervised learning techniques on the Spaceship Titanic dataset. The analysis explores patterns in passenger data and evaluates models for predicting transportation likelihood.

---

#### **Contents**
- `train.csv`: The dataset used for analysis.
- `code.ipynb`: Jupyter Notebook containing data preprocessing, visualization, clustering, and supervised learning models.
- `requirements.txt`: List of required Python libraries to run the code.
- `README.md`: Documentation for the project.

---

#### **Key Highlights**
1. **Data Analysis**:
   - Visualized relationships between features (e.g., HomePlanet, Destination, CryoSleep) and transportation outcomes.
   - Correlation and spending behavior insights were derived using heatmaps, bar charts, and box plots.

2. **Fitting: Supervised Learning**:
   - Trained Decision Tree, Random Forest, and AdaBoost models to predict the `Transported` feature.
   - Random Forest achieved the highest accuracy (79%), followed by AdaBoost (78%).

3. **Clustering**:
   - Performed K-Means clustering to group passengers based on spending, CryoSleep status, and age.
   - Identified actionable passenger groups:
     - High spenders with low transport likelihood.
     - CryoSleep passengers with the highest transport success rate.

---

#### **Setup Instructions**
1. Clone the repository:
   ```
   git clone https://github.com/Maneeshkumar08/Clustering-and-Fitting-on-Spaceship-Data.git
   ```
2. Navigate to the directory:
   ```
   cd Clustering-and-Fitting-on-Spaceship-Data
   ```
3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Open the notebook:
   ```
   jupyter notebook code.ipynb
   ```

---

#### **Results**
- **Insights from Clustering**:
  - CryoSleep is strongly associated with transportation success.
  - Low spenders are more likely to be transported compared to high spenders.
- **Model Performance**:
  - Random Forest outperformed other models in accuracy and robustness.

For further details, explore the `code.ipynb` file.
