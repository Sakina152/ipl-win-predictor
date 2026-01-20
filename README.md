# IPL Win Probability Predictor

This project is a Machine Learning application that predicts the winning probability of an IPL cricket match based on the current match situation. It uses a pre-trained model deployed with [Streamlit](https://streamlit.io/).

## Features
- Select Batting and Bowling teams from major IPL franchises.
- Choose the host city.
- Input current match stats: Target Score, Current Score, Overs Completed, and Wickets Out.
- View real-time win probabilities for both teams.

## Tech Stack
- **Python**: Core programming language.
- **Streamlit**: For the web interface.
- **Scikit-learn**: For the machine learning model (`pipe.pkl`).
- **Pandas**: For data manipulation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Sakina152/ipl-win-predictor
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the application locally:

```bash
streamlit run app.py
```

The app will open in your default browser at `http://localhost:8501`.

## Project Structure
- `app.py`: Main application script containing the Streamlit UI and prediction logic.
- `pipe.pkl`: Pickled machine learning model used for predictions.
- `requirements.txt`: List of Python dependencies.
- `Untitled.ipynb`: (Optional) Jupyter notebook used for data analysis and model training.
