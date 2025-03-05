# 🦠 Malaria Infection Detection using Image Classification

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![R Version](https://img.shields.io/badge/R-%3E%3D4.0-blue.svg)](https://www.r-project.org/)
[![Keras](https://img.shields.io/badge/Keras-R-red.svg)](https://keras.rstudio.com/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://tensorflow.rstudio.com/)

## 📊 Overview
This project demonstrates the application of deep learning for medical image classification, specifically focusing on detecting malaria infections in blood cell images. Using R with Keras and TensorFlow, we've developed a model that achieves approximately 95% accuracy in identifying parasitized cells, showcasing the potential of machine learning in medical diagnostics.

## ✨ Key Features
- **Advanced Image Classification**: Utilizes deep learning techniques to analyze blood cell images
- **High Accuracy**: ~95% accuracy on unique test data
- **R-Based Implementation**: Leverages R's powerful ecosystem for data science
- **Reproducible Research**: Complete documentation and code for replication

## 🔬 Technical Implementation
### Tools & Technologies
- **R**: Primary programming language
- **Keras/TensorFlow**: Deep learning framework
- **RStudio**: Development environment
- **ggplot2**: Data visualization

### Model Architecture
- Convolutional Neural Network (CNN) optimized for image classification
- Multiple convolutional and pooling layers
- Dropout layers for preventing overfitting
- Binary classification output (parasitized vs. uninfected)

## 📁 Project Structure
```bash
Project/
├── 📊 SCRIPTS/
│   └── Master Script.Rmd    # Main analysis notebook
├── 📁 DATA/                 # Dataset directory
│   ├── Raw Images/         # Original cell images
│   └── Processed/         # Preprocessed data
├── 📈 OUTPUT/              # Results and visualizations
│   └── output for model.pdf # Model performance analysis
└── 📝 Documentation/       # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- R (version 4.0 or higher)
- RStudio (recommended)
- Required R packages:
  ```r
  install.packages(c("keras", "tensorflow", "tidyverse", "ggplot2"))
  ```

### Dataset
The project uses the Malaria Cell Images Dataset from the National Library of Medicine. The dataset includes:
- Parasitized and uninfected cell images
- Balanced class distribution
- High-quality microscopy images

### Running the Analysis
1. Clone the repository
2. Open the `SCRIPTS/Master Script.Rmd` in RStudio
3. Install required packages
4. Run the analysis chunks sequentially

## 📈 Results & Performance
Our model demonstrates strong performance in malaria detection:
- **Accuracy**: ~95% on test data
- **Balanced Performance**: High sensitivity and specificity
- **Robust Validation**: Tested on unique, unseen data

## 🔍 Methodology
1. **Data Preprocessing**
   - Image standardization
   - Data augmentation
   - Train-test split

2. **Model Development**
   - CNN architecture design
   - Hyperparameter tuning
   - Cross-validation

3. **Evaluation**
   - Performance metrics
   - Visualization of results
   - Error analysis

## 📚 Further Reading
- [Original Dataset Source](https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#malaria-datasets)
- [WHO Malaria Information](https://www.who.int/health-topics/malaria)
- [Deep Learning in Medical Imaging](https://www.nature.com/articles/s41746-019-0189-7)

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments
- National Library of Medicine for the dataset
- R and Keras development teams
- UVA Data Science program

## 📬 Contact
Andre Chuabio
- GitHub: [@AndreChuabio](https://github.com/AndreChuabio)
- Project Link: [Malaria-Infection-Detection](https://github.com/AndreChuabio/Malaria-Infection-Detection)

---
⭐️ If you find this project interesting, please consider giving it a star!
