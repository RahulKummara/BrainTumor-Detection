# BrainTumor-Detector

## Overview
This project begins with a Jupyter Notebook where I preprocess an MRI brain image dataset and dive into why deep learning, especially CNNs, works well for this kind of problem. The notebook walks through building and tuning a CNN model, showing how it's great for image classification, especially with medical images like MRIs.

The choice of deep learning was driven by its proven capability in handling complex image recognition tasks, and CNNs were selected due to their effectiveness in image classification problems, particularly in identifying patterns and features in medical imaging.

Following the development and fine-tuning of the CNN model in the notebook, this project extends to the realm of practical application through a web interface. Built with Flask, the web application leverages the trained CNN model to provide real-time predictions on pre-loaded MRI images (subset of the test set). This integration not only showcases the model's capabilities in a user-friendly format but also demonstrates the potential of deep learning models in real-world applications.

## Setting Up the Flask Application
1. **Clone the Repository**:
    ```
    git clone https://github.com/RahulKummara/BrainTumor-Detection.git
    ```

2. **Navigate to the Project Directory**:
    ```
    cd BrainTumor-Detection
    ```

3. **Install Dependencies**:
- Ensure all required Python packages are installed:
  ```
  pip install -r requirements.txt
  ```

## Running the Flask Application
1. **Start the Flask Server**:
    ```
    python app.py
    ```
2. **Access the Application**:
- Open a web browser and go to `http://127.0.0.1:5000` to view the application.


## Technologies Used
- **Machine Learning**: TensorFlow, Keras, OpenCV
- **Image Processing**: PIL (Python Imaging Library)
- **Data Handling and Visualization**: Pandas, NumPy, Matplotlib, Seaborn
- **Frontend**: HTML, CSS
- **Backend**: Flask (Python web framework)


## Author
#### Rahul Kummara