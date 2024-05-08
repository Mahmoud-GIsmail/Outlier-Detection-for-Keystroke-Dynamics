# Outlier-Detection-for-Keystroke-Biometric-User-Authentication   [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11144535.svg)](https://doi.org/10.5281/zenodo.11144535)

**Authors:**

- Mahmoud G. Ismail
    - Faculty of Media Engineering and Technology, German University in Cairo, Cairo 11835, Egypt

- Mohammed A.-M. Salem
  - Faculty of Media Engineering and Technology, German University in Cairo, Cairo 11835, Egypt

- Mohamed A. Abd El Ghany
  - Electronics Department, German University in Cairo, Cairo 11835, Egypt
  - Integrated Electronic Systems Lab, TU Darmstadt, 64283 Darmstadt

- Eman Abdullah Aldakheel
  - Department of Computer Sciences, College of Computer and Information Sciences, Princess Nourah Bint Abdulrahman University, Riyadh 11671, Saudi Arabia

- Safia Abbas
  - Department of Computer Sciences, Faculty of Computer and Information Sciences, Ain Shams University, Cairo 11566, Egypt

**Corresponding Author:**

- Mahmoud G. Ismail
  - Email: mahmodg.ismail@gmail.com

## Overview

This repository houses the implementation for an innovative approach to keystroke dynamics-based authentication, featuring the Histogram-Based Outlier Score (HBOS). In the realm of information security, user authentication plays a critical role, necessitating robust measures against identity fraud and data breaches. The conventional challenge in keystroke dynamics research, particularly in real-world scenarios, lies in the dependency on imposter datasets. This project introduces a paradigm shift by employing unsupervised outlier detection techniques, with a focus on HBOS, thereby eliminating the need for imposter samples.

## Key Features

- **Alternative Outlier Detection Approach:** The implementation introduces an alternative paradigm in outlier detection, prominently featuring the Histogram-Based Outlier Score (HBOS).

- **Reduced Dependency on Imposter Data:** Departing from traditional reliance on imposter datasets, this project enhances the practical applicability of keystroke dynamics-based authentication by reducing dependence on extensive imposter data.

- **Addressing Real-World Challenges:** The implementation focuses on addressing challenges associated with simulating fraudulent keystrokes, catering to real-world scenarios where such challenges are paramount.

- **Comprehensive Evaluation:** The project conducts a thorough evaluation of HBOS against 15 other outlier detection methods, highlighting its superior performance.

4. **Explore Results:**
    After running the code, explore the results and performance metrics to gauge the effectiveness of the implemented keystroke dynamics-based authentication with HBOS.

## Results and Metrics

Upon execution, the system provides insightful metrics such as Equal Error Rate (EER), Area Under the Curve (AUC), and Accuracy (ACC), showcasing the reliability and efficiency of the proposed approach.

### EER, AUC, and ACC Scores

The following table displays the EER, AUC, and ACC scores for each classifier:

| Classifier                                   | EER (%) | ACC (%) | AUC (%) |
|----------------------------------------------|---------|---------|---------|
| Histogram-based Outlier Detection (HBOS)     | 6.42    | 90.55   | 97.68   |
| Isolation Forest                             | 8.89    | 87.24   | 96.34   |
| Principal Component Analysis (PCA)           | 10.45   | 79.39   | 94.74   |
| Gaussian Mixture Model                       | 11.00   | 81.90   | 94.44   |
| Average KNN                                  | 12.60   | 66.24   | 93.86   |
| Angle-based Outlier Detector (ABOD)          | 12.67   | 56.24   | 93.84   |
| K Nearest Neighbors (KNN)                    | 13.30   | 65.30   | 93.30   |
| Cluster-based Local Outlier Factor (CBLOF)   | 14.73   | 64.61   | 91.84   |
| Kernel Density Estimation                    | 15.62   | 61.36   | 90.11   |
| Feature Bagging                              | 16.92   | 57.77   | 89.76   |
| INNE                                         | 17.44   | 70.52   | 90.17   |
| Local Outlier Factor (LOF)                   | 17.60   | 56.93   | 89.09   |
| Locally Selective Combination (LSCP)        | 17.84   | 58.67   | 89.03   |
| One-class SVM (OCSVM)                        | 19.29   | 60.35   | 84.97   |
| LMDD                                         | 44.95   | 54.57   | 60.96   |

### ROC Curves

ROC curves are plotted for each group of classifiers:

![Linear Models](Figure%203.png)


## Additional Visualization

A separate visualization of the HBOS classifier is shown below:
![HBOS Classifier](Figure%204.png)

## Contributing

Contributions are welcome! Feel free to submit issues, feature requests, or pull requests. For major changes, please open an issue first to discuss potential updates.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

