# Detect-Cheating-In-Exam-Halls Project 👁️‼️
## Project Overview
This project focuses on **detecting cheating in exam halls using computer vision**.  
It is designed to **analyze images, recorded videos, or live camera feeds** to detect suspicious student behavior, aiming to enhance exam efficiency and maintain academic integrity.  
The goal is to provide an intelligent tool to assist invigilators and ensure fair and reliable testing conditions.  
This project was completed as part of the **final project for the Hash Plus Artificial Intelligence Bootcamp**.

---

## Tools and Technologies Used
- **YOLOv5**: Object detection and motion tracking in videos and images.  
- **PyTorch**: Building and running the deep learning model.  
- **OpenCV**: Image and video processing, real-time camera support.  
- **Kaggle**: Initial model training.  
- **Jupyter Notebook**: Practical application and testing.  
- **Roboflow**: Data collection and dataset augmentation.

---

## How the Project Works
1. **The Dataset**:  
   - The dataset `main/Dataset.zip` contains sample images used for training and testing the model.  

2. **Training on Kaggle**:  
   - The notebook `Notebooks/ModelTraining-Kaggle.ipynb` is used to train the model on the dataset.  

3. **Testing on Jupyter Notebook**:  
   - The notebook `Notebooks/Cheating detection- Jupyter notebook.ipynb` is used to test the model on new videos, images, or live camera feeds.  

4. **Real-Time Detection**:  
   - The model can run on:  
     - Recorded videos  
     - Individual images  
     - Live camera feed (real-time detection)

---

## Key Features
- Real-time cheating detection using live camera input.  
- Supports recorded videos and static images.  
- High accuracy model trained with **YOLOv5 and PyTorch**.  
- Easy-to-use Jupyter Notebook interface for rapid testing.  
