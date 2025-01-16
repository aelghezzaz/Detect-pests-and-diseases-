## Overview:

This project involves the Management System for Moroccan Agriculture 🌱

- Detect pests and diseases: "Potato-Leaf-Disease-Classification-using-CNN"
  
## Problem Statement :

Every year, farmers suffer economic losses and crop waste due to various diseases affecting potato plants. Among these diseases, Early Blight and Late Blight are particularly devastating to potato leaf health. The significant yield losses experienced by potato growers are largely attributed to these ailments. Consequently, images are categorized into three classes:

- Potato Late Blight

- Potato Early Blight

- Potato Healthy Leaf

The process entails multiple steps, starting with the importation of libraries, loading and visualization of data, partitioning the data into training and validation sets, preprocessing the data, constructing the CNN model, training the model, and evaluating its performance.

The dataset can be accessed on Kaggle: https://www.kaggle.com/datasets/arjuntejaswi/plant-village

Web application to detect potato plant leaf diseases 🍃

huggingface : https://huggingface.co/spaces/MoroccanDS/Moroccan-Agri-Leaf-Pest-Detection

In this project we aim to build a web app that can assist farmers in detecting potato plant diseases. 

The application will be able to classify the disease in an infected potato plant using it's leaf and Convolutional Neural Networks.


## Requirements

* Python 3.9 or later
* Flask
* gunicorn
* streamlit
* tensorflow
* pillow
* numpy
  
## Installation

1. Clone the repository :
```bash
git clone https://github.com/Moroccan-Data-Scientists/Management-System-for-Moroccan-Agriculture-
```
2. Navigate to the project directory  :
```bash
cd Moroccan-Data-Scientists/Management-System-for-Moroccan-Agriculture-
```
3. Create a virtual environment and activate it using your preffered shell :
```bash
python -m venv venv
source venv/bin/activate
```
4. Install the required dependencies :
```bash
pip install -r requirements.txt
```
5. Start the Flask web application locally using Gunicorn(or Flask) :
```bash
gunicorn app:app
```
```bash
flask run
```
6. Start the streamlit web application :
```bash
streamlit run streamlit_app.py
```
7. The application will be available at :
* If you used Gunicorn: <http://127.0.0.1:8000/>
* If you used flask run: <http://127.0.0.1:5000/>
* If you used streamlit: <http://localhost:8501/>
8. Example of usage :
- Streamlit:
![Streamlit](https://cdn.hashnode.com/res/hashnode/image/upload/v1714150183694/179de6e2-c88a-4412-99a5-e382080a6ea5.png?auto=compress,format&format=webp)
![Streamlit](https://cdn.hashnode.com/res/hashnode/image/upload/v1714150321630/d5a5465c-5f4d-487c-9e7a-7709f13b9045.png?auto=compress,format&format=webp)
