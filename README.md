# TrueSound - Hindi Audio Deepfake Detection

## Overview
**TrueSound** is a machine learning-based system that detects and classifies deepfake audio clips in the Hindi language. It helps distinguish between real and synthetically manipulated audio to promote content authenticity and combat misinformation.


## Features
- Extraction of audio features (MFCCs) using Librosa
- Synthetic fake audio generation (pitch shift, speed change, noise)
- Binary classification using Logistic Regression
- Visualization using confusion matrix
- Accurate detection of real vs. fake Hindi speech clips


## Technologies Used
- Python
- Scikit-learn
- Librosa
- NumPy / Pandas
- Matplotlib / Seaborn


## Dataset
The dataset includes Hindi language audio clips obtained from the [Indian Languages Audio Dataset](https://www.kaggle.com/datasets/hmsolanki/indian-languages-audio-dataset).  
Fake audio clips are synthetically generated using pitch shifting, time stretching, and noise addition techniques.


## How to Use
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install librosa scikit-learn matplotlib seaborn
3. Run the TrueSound.ipynb notebook step-by-step
4. Evaluate results and model performance


## Contributions
Contributions are welcome! Fork the repository and open a pull request with improvements or new features.


## License
This project is licensed under the MIT License.


## Acknowledgements
- Kaggle - Indian Languages Audio Dataset
- The open-source Python ML and audio processing community
