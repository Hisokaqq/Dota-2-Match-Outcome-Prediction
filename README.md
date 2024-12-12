


# Dota 2 Match Outcome Prediction using Machine Learning

This project leverages machine learning to analyze and predict the outcomes of Dota 2 matches based solely on hero picks. By exploring hero win rates, matchups, and synergies, it provides insights into how hero selection impacts team success.

---

## Project Structure

```plaintext
├── data/                  # Folder containing preprocessed data files (heroes, matches, synergies, etc.)
├── images/                # Folder for project-related images or visualizations
├── main.ipynb             # Jupyter Notebook for analysis, visualization, and experimentation
├── main.py                # Python script for core functionalities and automation
├── requirements.txt       # Python package dependencies for the project
```

---

## Features

- **Hero Matchup Analysis**: Calculates how heroes counter each other based on historical match data.
- **Team Synergy Scores**: Evaluates how well heroes perform together on the same team.
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting
- **Hyperparameter Tuning**: Optimized models using grid search for the best predictive accuracy.
- **Visualization**: Heatmaps for hero matchups and synergies, and distributions of win rates.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dota2-prediction.git
   cd dota2-prediction
   ```

2. Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the project:
   - Use `main.ipynb` for an interactive notebook experience.
   - Use `main.py` for running the core pipeline.

---

## Usage

- **Skip Data Fetching**: Load preprocessed data directly from the `data` folder.
- **Train and Evaluate Models**: Experiment with different machine learning models to predict match outcomes.
- **Analyze Hero Interactions**: Generate heatmaps and insights from hero matchup and synergy data.

---

## Data Source

- **OpenDota API**: Hero stats and public matches are fetched via [OpenDota API](https://docs.opendota.com/).

---

## Results

- Random Forest achieved the highest prediction accuracy of approximately **63-65%**.
- Hero synergy and matchup scores significantly influenced the predictions.

