# Energy Prediction Project

A machine learning project for predicting energy consumption using CNN-LSTM neural networks.

##  Project Structure

```
├── data/
│   ├── raw_data/           # Original dataset files
│   └── processed_data/     # Cleaned and preprocessed data
├── models/                 # Trained model files
├── notebooks/              # Jupyter notebooks for analysis
│   ├── pre_processing.ipynb
│   └── baseline_model.ipynb
└── requirements.txt        # Python dependencies
```

##  Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/manodyaNrathnyaka/Energy_prediction.git
   cd Energy_prediction
   ```

2. **Create and activate virtual environment:**
   ```bash
   python -m venv energy
   # On Windows:
   energy\Scripts\activate
   # On Mac/Linux:
   source energy/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

##  Data Requirements

This project requires energy consumption dataset.:
- dataset:https://drive.google.com/file/d/1ZkR70gAxSUoU5b1KqvTW4bdFM0il-nZz/view?usp=sharing
- Place the data set at raw data files in `data/raw_data/` directory

**Note:** Data files are not included in this repository due to size.

## Usage

1. **Data Preprocessing:** Run `notebooks/pre_processing.ipynb` to clean and prepare your data
2. **Model Training:** Use `notebooks/baseline_model.ipynb` to train the CNN-LSTM model
3. **Model Files:** Trained models will be saved in the `models/` directory

## Model Architecture

The project implements a CNN-LSTM hybrid model for time series energy prediction:
- **CNN layers** for feature extraction
- **LSTM layers** for temporal pattern learning
- Suitable for multivariate time series forecasting

##  Requirements

See `requirements.txt` for full list of dependencies.

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## License

This project is open source and available under the [MIT License](LICENSE).
