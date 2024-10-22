![Project Cover Photo](./images/AI%20Activity%20Recognition%20for%20HMDS%20Project%20Cover.png)

### 1. Overview
- **Human Activity Recognition (HAR):** The project explores the application of HAR models for head-mounted displays (HMDs), aiming to generalise from mobile phone-based models to HMD data.
- **Data Collection:** Developed a Unity-based VR app, "Saimon Says," to collect HMD accelerometer data.
- **Cross-Domain Generalisation:** The project investigates whether machine learning models trained on mobile phone data can be effectively applied to HMDs.

### 2. Motivation
- **Emerging Need for HAR in HMDs:** As HMDs are increasingly used in sectors like healthcare, gaming, and productivity, HAR systems become essential for improving user safety and experience.
- **Cross-Device Generalisation:** The challenge lies in generalising well-established phone-based HAR models to HMDs, where motion patterns differ significantly. The value is in being able to harness existing data to improve forward facing models.

### 3. Objectives
- **Model Development:** Establish HAR models based on the WISDM dataset for phone data.
- **HMD Data Collection:** Create and collect activity data via the custom-built "Saimon Says" VR app.
- **Model Generalisation:** Evaluate and improve phone-based models for effective use in HMD environments.

### 4. Technologies Used
- **Machine Learning Models:** Decision tree, logistic regression, neural network, and gradient boosting classifiers.
- **Data Collection Tools:** Unity Engine and SteamVR for HMD data collection.
- **Processing:** Feature selection techniques like Recursive Feature Elimination with Cross-Validation (RFECV) to enhance model accuracy.

### 5. Challenges and Solutions
- **Cross-Domain Adaptation:** Initial models showed a significant drop in accuracy when applied to HMD data due to different motion patterns. Fine-tuning and combined training were used to address this.
- **Data Limitations:** The small scale of the HMD dataset was compensated by combining it with phone data to improve model generalisation.
- **Feature Engineering:** RFECV and permutation feature importance were critical to identify domain-robust features and improve cross-device model performance.

### 6. Results & Impact
- **Improved Generalisation:** After fine-tuning, the decision tree and gradient boosting models achieved above 90% accuracy on HMD data.
- **Significant Contributions:** The study showcases that, with careful preprocessing and tuning, HAR models trained using phone data can be adapted to work effectively on HMDs.
- **Future Applications:** The project sets a foundation for future work in extending HAR models to VR environments, with potential real-time applications in gaming, healthcare, and productivity.

# Appendix

## Appendix A | Project Poster

![Project Poster](./images/Project%20Poster.png)

**Figure 1.** The poster presentation for the project.