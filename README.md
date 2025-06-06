# Waves Don't Lie: Leveraging Test Time Training and Kolmogorov Arnold Networks for EEG Based Biometrics

![Best Paper Award](https://img.shields.io/badge/ICBSII%202025-Best%20Paper%20Award-gold)
![Research](https://img.shields.io/badge/Research-EEG%20Biometrics-blue)
![Models](https://img.shields.io/badge/Models-KAN%20%7C%20TTT%20%7C%20LSTM-brightgreen)

## 🏆 Award
This project received the **Best Paper Award** at the International Conference on Biometric Systems and Intelligence (ICBSII 2025) hosted by SSN near Kalavakkam, Chennai on March 28, 2025.

## 📝 Abstract
This repository contains the implementation of our paper "Waves Don't Lie: Leveraging Test Time Training and Kolmogorov Arnold Networks for EEG Based Biometrics." We address the inherent variability in EEG signals through advanced deep learning approaches, comparing the performance of Kolmogorov Arnold Networks (KAN), Test Time Training (TTT) enhanced frameworks, and LSTM as a baseline model for EEG-based biometric authentication.

## 🧠 Background
EEG-based biometric systems face significant challenges due to the non-stationary nature of brain signals and their susceptibility to temporal variations. Our research explores how modern neural network architectures, particularly KANs and test-time adaptation techniques, can improve the robustness of these systems over traditional approaches.

## 📊 Dataset
Our evaluation integrated two primary data sources:
- Newly collected EEG data from volunteer participants (in collaboration with Nithish Ariyha K and Giri Prasath R)
- An existing standard EEG dataset (contained in `eegdata.mat`)

## 🔬 Methodology

### Data Analysis
Comprehensive analysis of EEG signal characteristics is available in `Data_analysis.ipynb`. This notebook contains preprocessing steps, feature extraction, and exploratory data analysis.

### Model Development
The core implementation of our model architectures is contained in `Model_Started_cooking_tbh.ipynb`. This notebook includes:

- Implementation of the Kolmogorov Arnold Network (KAN) architecture
- Test Time Training (TTT) framework development
- LSTM baseline model implementation
- Training procedures and hyperparameter tuning
- Cross-validation and evaluation metrics

### Additional Experiments
- `Tinkering.ipynb`: Early experimental approaches and feature engineering
- `Waste_of_time.ipynb` & `Waster_of_time.ipynb`: Documented unsuccessful approaches (retained for research transparency)
- `Don't_look.ipynb`: Contains preliminary experiments and debug code

## 📈 Results
Our model comparison demonstrated that the KAN architecture, enhanced with Test Time Training, significantly outperforms traditional LSTM models in addressing the non-stationarity of EEG signals. Key improvements were observed in:

- Robustness to session-to-session variability
- Subject-specific identification accuracy
- Adaptation to changing mental states

## 🔧 Trained Models
The repository includes pre-trained models:
- `best_model.pth`: Final KAN model with optimal parameters
- `best_model_latest.pth`: Updated version with additional training
- `ttt_model_results.pth`: Test Time Training enhanced model results

## 🚀 Usage
To reproduce our results:

1. Clone this repository
2. Ensure dependencies are installed (see requirements section)
3. Run the data analysis notebook first: `jupyter notebook Data_analysis.ipynb`
4. Train and evaluate models: `jupyter notebook Model_Started_cooking_tbh.ipynb`

## 📋 Requirements
- Python 3.8+
- PyTorch 2.0+
- NumPy
- SciPy
- Jupyter
- MNE-Python (for EEG processing)
- Scikit-learn

## 👥 Contributors
- Eshwanth Karti T R
- Nithish Ariyha K
- Vikash J
- Yeshwanth Balaji
- Giri Prasath R

## 🎓 Supervision
This research was conducted under the valuable guidance of Dr. AMRUTHA V.

## 📚 Publication
The full paper is available on ResearchGate: [https://lnkd.in/gDzkfcPG](https://lnkd.in/gDzkfcPG)

## 🙏 Acknowledgments
We extend our sincere gratitude to:
- The judges and organizing committee of ICBSII 2025
- All volunteers who participated in our EEG data collection

## 📞 Contact
For any inquiries regarding this research, please contact eshwanthkartitr@gmail.com.