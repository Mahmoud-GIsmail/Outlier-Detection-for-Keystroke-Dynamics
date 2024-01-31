# Outlier-Detection-for-Keystroke-Biometric-User-Authentication

## Overview

This repository houses the implementation for an innovative approach to keystroke dynamics-based authentication, featuring the Histogram-Based Outlier Score (HBOS). In the realm of information security, user authentication plays a critical role, necessitating robust measures against identity fraud and data breaches. The conventional challenge in keystroke dynamics research, particularly in real-world scenarios, lies in the dependency on imposter datasets. This project introduces a paradigm shift by employing unsupervised outlier detection techniques, with a focus on HBOS, thereby eliminating the need for imposter samples.

## Key Features

- **Alternative Outlier Detection Approach:** The implementation introduces an alternative paradigm in outlier detection, prominently featuring the Histogram-Based Outlier Score (HBOS).

- **Reduced Dependency on Imposter Data:** Departing from traditional reliance on imposter datasets, this project enhances the practical applicability of keystroke dynamics-based authentication by reducing dependence on extensive imposter data.

- **Addressing Real-World Challenges:** The implementation focuses on addressing challenges associated with simulating fraudulent keystrokes, catering to real-world scenarios where such challenges are paramount.

- **Comprehensive Evaluation:** The project conducts a thorough evaluation of HBOS against 15 other outlier detection methods, highlighting its superior performance.

## Getting Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/keystroke-authentication.git
    cd keystroke-authentication
    ```

2. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Code:**
    ```bash
    python main.py
    ```

4. **Explore Results:**
    After running the code, explore the results and performance metrics to gauge the effectiveness of the implemented keystroke dynamics-based authentication with HBOS.

## Results and Metrics

Upon execution, the system provides insightful metrics such as Equal Error Rate (EER), Area Under the Curve (AUC), and Accuracy (ACC), showcasing the reliability and efficiency of the proposed approach.

## Contributing

Contributions are welcome! Feel free to submit issues, feature requests, or pull requests. For major changes, please open an issue first to discuss potential updates.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---
