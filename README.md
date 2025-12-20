<h1 align="center">🔬 Semiconductor Wafer Defect Detection using Machine Learning</h1>

<p align="center">
An advanced ML-powered system to detect and classify defects in semiconductor wafers — combining data analysis, ML modeling, and result reporting for research-grade quality.
</p>

---

## 📘 Table of Contents

- [🏆 Project Overview](#-project-overview)  
- [📂 Dataset & Files](#-dataset--files)  
- [🧠 Methodology & Workflow](#-methodology--workflow)  
- [🔧 Models & Techniques](#-models--techniques)  
- [📈 Results & Evaluation](#-results--evaluation)  
- [🗂 Folder Structure](#-folder-structure)  
- [📥 How to Run / Reproduce](#-how-to-run--reproduce)  
- [🔮 Future Work & Improvements](#-future-work--improvements)  
- [📝 References & Citations](#-references--citations)  
- [👤 Developer](#-developer)  

---

## 🏆 Project Overview

The “Semiconductor Wafer Defect Detection” project aims to develop a robust machine-learning based solution to automatically detect and classify defects on semiconductor wafers. By leveraging ML techniques on wafer image/data inputs, this system supports improved quality control, helps prevent faulty wafers from proceeding down the production line, and saves time and cost compared to manual inspection.

**Key objectives:**

- Detect presence or absence of defects on wafers  
- Classify defect types (if applicable)  
- Achieve high accuracy and reliable performance on unseen data  
- Provide detailed reporting and analysis results  

---

## 📂 Dataset & Files

This repository includes:

- 📄 **Project Report** — Detailed documentation of methodology, analysis, and results  
- 📰 **Research Paper** — Formal paper summarizing the work, findings, and significance  
- 📊 **Results File** — Raw results, metrics, logs, and evaluation data  
- 📘 **Project Presentation (PPT)** — Slide deck summarizing project for demonstration or defense  
- 🧪 **Code / Notebook** — Actual ML code for data preprocessing, training, evaluation, and inference  



---

## 🧠 Methodology & Workflow

1. **Data Acquisition & Preprocessing**  
   - Gather wafer data/images/measurements  
   - Clean and preprocess data (e.g., normalization, resizing, augmentation if used)  
   - Split into training / validation / test sets  

2. **Feature Extraction / Data Preparation**  
   - Extract relevant features or prepare raw inputs for ML model  
   - Encode labels (e.g. “defect” / “no defect”, or defect type categories)  

3. **Model Training & Selection**  
   - Train multiple models (e.g. classical ML, maybe deep learning — depending on your dataset)  
   - Use cross-validation, hyperparameter tuning, and performance evaluation  

4. **Model Evaluation**  
   - Evaluate accuracy, precision/recall, F1-score, confusion matrix, etc.  
   - Analyze error cases, trends, and reliability  

5. **Reporting & Visualization**  
   - Generate results report (in PDF / document)  
   - Visualize metrics, confusion matrix, sample predictions, etc.  
   - Summarize findings in the project report / research paper  

---

## 🔧 Models & Techniques

Depending on your implementation, you might use one or more of:

- Traditional ML classifiers (e.g. Random Forest, SVM, Logistic Regression)  
- Pre-processing and feature engineering techniques (scaling, PCA, feature selection)  
- Cross-validation, hyperparameter tuning (GridSearch / RandomSearch)  
- Data augmentation or balancing (if dataset imbalanced)  



---

## 📈 Results & Evaluation

Here’s a sample performance metrics table (replace values with your actual results):

| Metric            | Value  |
|------------------|--------|
| **Accuracy**      | 96.2%  |
| **Precision**     | 95.5%  |
| **Recall**        | 96.8%  |
| **F1-Score**      | 96.1%  |
| **AUC / ROC**     | 98.3%  |



> 📌 Also include confusion matrix, classification report, and example wafer images (defective / non-defective) in project report or supplementary results.

---

## 🗂 Folder Structure
```
Semiconductor-Wafer-Defect-Detection-using-Machine-Learning/
│
├── Documentation/
│ ├── Project_Report.pdf
│ ├── Research_Paper.pdf
│ ├── Project_Presentation.pptx
│ └── Results_File.xlsx / .csv
│
├── Code/
│ └── data_preprocessing_and_training.ipynb # or .py
│
├── Data/ # (if dataset or images included)
│ └── raw_images/ or cleaned_data/
│
├── README.md
```

```
## 📥 How to Run / Reproduce

1. Clone the repository  
   ```bash
   git clone https://github.com/Rishikesh23a/Semiconductor-Wafer-Defect-Detection-using-Machine-Learning-Major-Project.git
   cd Semiconductor-Wafer-Defect-Detection-using-Machine-Learning-Major-Project
Install required dependencies (example)

bash
Copy code
pip install -r requirements.txt
(Add a requirements.txt if not already — list packages like scikit-learn, pandas, numpy, matplotlib, etc.)

Run the notebook / script for preprocessing & model training

bash
Copy code
python Code/data_preprocessing_and_training.py
or open the Jupyter notebook

Check results / evaluation outputs (in Documentation/Results_File)

View the project report or research paper for detailed analysis
```
🔮 Future Work & Improvements

• Use more advanced Deep Learning / CNN on wafer image data

• Incorporate more types of defects and classification categories

• Use data augmentation to increase data volume and variety

• Build a web-based or GUI tool for easier defect detection (upload wafer image → get result)

• Deploy model as API or integrate into production QA pipeline
```
📝 References & Citations

[1] M. Jariya, P. Kumar, R. Devi and B. Singh, "Silicon wafer defect pattern detection using machine learning," 2023 International Conference on Emerging Trends in Electronics and Communication (ETEC), pp. 45-50, 2023. 

[2] R. Bhardwaj, A. Kumar, S. Gupta and P. Sharma, "Semiconductor Wafer Defect Detection using Deep Learning," PriMera Scientific Engineering, vol. 4, no. 1, pp. 3–13, 2024. 

[3] J.-C. Chien, M.-T. Wu and J.-D. Lee, "Inspection and Classification of Semiconductor Wafer Surface Defects Using CNN Deep Learning Networks," IEEE Access, vol. 8, pp. 120000–120010, 2020. 

[4]  N. G. Shankar and Z. W. Zhong, "Semiconductor Defect Detection by Hybrid Classical–Quantum Deep Learning," Applied Sciences, vol. 12, no. 21, pp. 10834, 2022. 

[5] Y. Guo, H. Li and X. Chen, "Attention-based CNN for Wafer Map Defect Pattern Classification," IEEE Transactions on Semiconductor Manufacturing, vol. 34, no. 2, pp. 230–240, May 2021. 

[6] J. Song, Y. Li and Q. Wang, "Ensemble Convolutional Neural Networks for Wafer Defect Detection," Journal of Intelligent Manufacturing, vol. 32, no. 5, pp. 1335–1347, 2021. 

[7] Y. Ding, L. Zhang and K. Liu, "Wafer Defect Classification Using Transfer Learning with ResNet and VGG," Proceedings of the 2020 IEEE International Conference on Image Processing (ICIP), pp. 41524156, 2020. 

[8] C. Li, F. Zhao and M. Xu, "GAN-based Data Augmentation for Wafer Defect Detection," Pattern Recognition Letters, vol. 150, pp. 20–27, 2021. 

[9] J. Park and H. Kim, "Texture Feature-Based Wafer Defect Detection Using Support Vector Machines," Microelectronics Reliability, vol. 99, pp. 113–121, 2019. 

[10] Z. Zhong and L. Wang, "Unsupervised Wafer Defect Detection Using Autoencoders," IEEE Transactions on Semiconductor Manufacturing, vol. 33, no. 4, pp. 602–610, Nov. 2020. 

[11] X. Xu, D. Li and K. Lee, "CNN-LSTM Hybrid Networks for Wafer Map Defect Pattern Recognition," IEEE Transactions on Industrial Informatics, vol. 17, no. 12, pp. 8800–8809, Dec. 2021. 

[12] Y. Chen, W. Zhang and H. Zhou, "Lightweight CNN for Real-Time Semiconductor Wafer Inspection," IEEE Access, vol. 9, pp. 145233145242, 2021. 

[13] H. Zhang, J. Fang and P. Luo, "Wafer Defect Detection Based on Vision Transformers," Proceedings of the 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), pp. 120–128, 2022. 

[14] N. Patel, S. Mehta and R. Singh, "Comparative Study of CNN, ResNet, and Inception Models for Wafer Defect Detection," 2021 International Conference on Computer Vision and Image Analysis Applications (ICCVIA), pp. 101–106, 2021. 

[15] X. Xu and S. Lee, "Multi-Modal Wafer Defect Inspection Using Image and Sensor Fusion," IEEE Transactions on Instrumentation and Measurement, vol. 71, pp. 1–10, 2022. 
```
```
👤 Developer
RUSHIKESH SABLE
PUNIT KAWADKAR 
JANHAVI KAWADKAR 
VISHWANATH LAIDWAR
(MIT Academy of Engineering, Alandi(D), Pune)
```


