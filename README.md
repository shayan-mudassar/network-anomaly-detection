# Network Anomaly Detection System

## Overview
This project focuses on building a Network Intrusion Detection System (NIDS) using machine learning techniques, specifically k-means clustering and Random Forest classifiers. By leveraging the KDDCUP99 dataset, the system effectively detects and classifies network anomalies, including Denial of Service (DOS), R2L, U2R, and Probing attacks.

## Features
- **Binary and Multinomial Classification**: Detect normal network activity and classify specific attack types.
- **Feature Engineering**: Attribute Ratio (AR)-based feature selection for improved performance.
- **Machine Learning Models**: Combines unsupervised k-means clustering with supervised Random Forest classifiers.
- **Comprehensive Evaluation**: Precision, recall, F1 score, and ROC curve for model assessment.
- **Scalable Deployment**: Ready for real-time network monitoring.

## Dataset
The project uses the **KDDCUP99 dataset**, a widely used benchmark dataset for network intrusion detection. It includes a variety of network traffic examples, both benign and malicious, enabling robust model training and evaluation.

## Methodology
1. **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
2. **Feature Selection**: Using AR-based methods to identify key features.
3. **Clustering and Classification**:
   - Apply k-means to group similar data points.
   - Train Random Forest classifiers on clustered data for improved accuracy.
4. **Model Evaluation**: Assess performance using detailed metrics and confusion matrices.
5. **Deployment Plan**: Strategies for integrating the system into operational networks.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shayan02/network-anomaly-detection.git
   cd network-anomaly-detection
   ```
2. Run the project:
   ```bash
   python main.py
   ```

## Usage
- Modify the configuration file to specify dataset paths and parameters.
- Run the scripts to preprocess data, train models, and evaluate performance.
- Use the trained model to monitor network traffic for anomalies.

## Results
The system demonstrates high accuracy in detecting and classifying various types of network attacks. Performance metrics and visualizations are included in the project for detailed analysis.

## Future Enhancements
- Incorporate deep learning models for better handling of complex patterns.
- Adapt the system for real-time data streams.
- Expand testing with more recent and diverse datasets.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request to propose changes or report bugs.

## Acknowledgments
- **Dataset**: [KDDCUP99 Dataset](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)
- **Techniques**: Inspired by advancements in machine learning for cybersecurity.

