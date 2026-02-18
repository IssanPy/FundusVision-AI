Retinal Eye Disease Detection

An AI-based system for identifying eye diseases from retinal fundus images using MATLAB.
This project focuses on automated analysis of fundus photographs to assist in early detection of retinal abnormalities.

📌 Overview

Retinal diseases such as diabetic retinopathy, glaucoma, and other pathological conditions can lead to severe vision impairment if not detected early. Manual diagnosis requires expert ophthalmologists and can be time-consuming.

This project aims to:

Process retinal fundus images

Extract meaningful visual features

Train a machine learning model

Classify images based on disease presence

The system is implemented using MATLAB and leverages image processing and machine learning techniques for medical image analysis.

🧠 Methodology

Image Acquisition
Fundus images are collected from a dataset of retinal scans.

Preprocessing

Image resizing

Noise reduction

Contrast enhancement

Normalization

Feature Extraction
Relevant features are extracted from the retinal images to highlight structural and pathological variations.

Model Training
A machine learning model is trained to classify the images into disease categories.

Evaluation
Model performance is evaluated using standard metrics such as accuracy.

🛠 Technologies Used

MATLAB

Image Processing Toolbox

Machine Learning techniques

Fundus image dataset

📊 Results

The trained model demonstrates reliable classification performance on the provided dataset. Further improvements can be achieved using larger datasets and deep learning architectures.

📂 Project Structure
/dataset              → Fundus image dataset  
/preprocessing        → Image processing scripts  
/model                → Training and classification code  
/results              → Output predictions and analysis  
main.m                → Main execution script  

🚀 How to Run

Open MATLAB.

Load the project folder.

Run main.m.

Ensure the dataset path is correctly configured.

🔬 Future Improvements

Implement deep learning models (CNN-based architectures)

Improve preprocessing for better vessel enhancement

Expand dataset for improved generalization

Develop a simple GUI for clinical usability

👨‍💻 Author

Developed as an academic project focused on medical image analysis and AI-driven healthcare applications.
