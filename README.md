

# **Bidirectional RNN for Sentiment Analysis**

## **1. Project Overview**
This project implements a Bidirectional Recurrent Neural Network (BiRNN) using a Bidirectional Long Short-Term Memory (BiLSTM) architecture for sentiment analysis on movie reviews. The task is to classify text data into two categories: positive or negative sentiment, based on the IMDB dataset.

## **2. Requirements**

Before running the project, make sure you have the following libraries installed:

- **Python**: Version 3.6 or higher
- **TensorFlow**: Version 2.x
- **NumPy**: For numerical operations
- **Matplotlib**: For plotting accuracy and loss graphs
- **TensorFlow Datasets**: To load the IMDB dataset

### **Install required libraries**:

You can install the necessary Python packages using pip:

```bash
pip install tensorflow numpy matplotlib tensorflow-datasets
```

## **3. Dataset**
The project uses the **IMDB movie reviews dataset**, which is available in TensorFlow Datasets (TFDS). The dataset contains 50,000 movie reviews labeled as positive or negative, split into training and testing sets.

## **4. Model Architecture**
The model follows this structure:
1. **Embedding Layer**: Converts the integer sequence into dense vectors.
2. **Bidirectional LSTM Layer**: Processes the input sequence in both forward and backward directions to capture context from both past and future.
3. **Dense Layers**: A fully connected layer with ReLU activation and a final output layer with a sigmoid activation for binary classification.

## **5. Usage Instructions**

### **5.1. Clone or Download the Repository**
Clone or download the repository containing the project files to your local machine:

```bash
git clone <repository_url>
```

### **5.2. Run the Model**
To run the model, execute the Python script (`model.py`). This will automatically download the IMDB dataset, preprocess it, and train the BiLSTM model.

```bash
python model.py
```

### **5.3. Visualize Training Performance**
After the model finishes training, it will plot the following graphs:
- **Training and Validation Accuracy**
- **Training and Validation Loss**

These plots will help you evaluate the model’s performance across epochs.

### **5.4. Model Architecture Visualization**
The architecture of the Bidirectional LSTM model is saved as an image (`model_architecture.png`) and can be found in the project directory.

To view the model architecture, open the `model_architecture.png` file.

---

## **6. Files in the Repository**
- **model.py**: The main Python script for building, training, and evaluating the BiRNN model.
- **README.md**: This file with instructions and details about the project.
- **model_architecture.png**: A graphical representation of the model architecture.
- **accuracy_loss_plots**: Folder containing the plots for accuracy and loss.

---

## **7. License**
This project is licensed under the MIT License.

---

## **8. Contact Information**
For any questions or issues related to the project, feel free to reach out to:

- **Name**: Anmol
- **Email**: anmolaggarwal8685@gmail.com



