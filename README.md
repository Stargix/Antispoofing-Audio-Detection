# 🛡️ Anti-Spoofing Audio Detection

This project tackles the challenge of detecting spoofed audio using machine learning techniques. Spoofed audio refers to manipulated or synthesized voice recordings used to impersonate individuals, often in biometric authentication systems. Our goal is to build a robust classifier capable of distinguishing between genuine and spoofed audio samples.

## 📁 Project Structure

- `nb-Antispoofing-Audio-Detection.ipynb`: Main notebook containing the end-to-end process: data loading, preprocessing, feature extraction, model training, and evaluation.

## 🔍 Overview

The pipeline includes:

- **Dataset Handling**: Loading and managing genuine and spoofed audio data.
- **Feature Extraction**: Leveraging Mel Frequency Cepstral Coefficients (MFCCs) and other audio features to represent voice signals.
- **Model Training**: Using machine learning models (e.g., SVM, Logistic Regression) to learn from extracted features.
- **Evaluation**: Assessing model performance with appropriate metrics (e.g., accuracy, confusion matrix).

## 🧠 Models Used

- KNN
- Decision Tree
- Support Vector Machine (SVM)

## 📊 Results

The models were evaluated on their ability to detect spoofed audio. Key results include:

- Accuracy on test data
- Confusion matrix for detailed performance insight
- Feature importance and decision boundary analysis

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/anti-spoofing-audio-detection.git
   cd anti-spoofing-audio-detection
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook nb-Antispoofing-Audio-Detection.ipynb
   ```

## 🛠️ Requirements

- Python 3.x
- Jupyter Notebook
- numpy, pandas, librosa, sklearn, matplotlib

## 📌 Notes

- Audio files and metadata are assumed to be preloaded or available via paths defined in the notebook.
- This project is for educational and research purposes.

## 📬 Contact

For questions or collaboration opportunities, feel free to reach out to:
- **Author**: Sergi Flores
