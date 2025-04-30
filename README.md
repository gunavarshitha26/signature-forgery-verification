# 🖋️ Signature Forgery Verification

A machine learning and deep learning-based system for offline signature verification. This project detects whether a given signature is genuine or forged using image processing techniques and classification algorithms such as CNN, SVM, KNN, and LSTM.

## 🚀 Features

- Offline signature verification using scanned images
- CNN + HOG-based feature extraction
- Decision Tree-based feature selection
- Multiple classifier support: SVM, KNN, LSTM
- Performance evaluation using Accuracy, Precision, Recall, and F1-Score
- GUI built using Tkinter for user interaction

## 📊 Performance

| Metric     | Value  |
|------------|--------|
| Accuracy   | ~97%   |
| Loss       | ~0.35  |
| Precision  | ~85%   |
| Recall     | ~83%   |
| F1-Score   | ~84%   |

## 🧠 Algorithms Used

- **CNN (Convolutional Neural Network)** – Feature extraction
- **HOG (Histogram of Oriented Gradients)** – Edge-based features
- **Decision Tree** – Feature selection
- **SVM, KNN, LSTM** – Classification

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: NumPy, OpenCV, scikit-learn, TensorFlow/Keras, matplotlib, Tkinter  
- **IDE**: Jupyter Notebook / VS Code

## 🗂️ Dataset

A labeled dataset of offline signatures (genuine and forged) is required. You may use public datasets like the [CEDAR Signature Dataset](http://www.cedar.buffalo.edu/NIJ/data/signatures.rar).

## 🧩 Project Structure
signature-forgery-verification/ │ ├── data/ # Dataset files ├── models/ # Trained models ├── src/ # Source code │ ├── preprocessing.py │ ├── feature_extraction.py │ ├── classifiers.py │ ├── evaluate.py │ └── gui_app.py ├── results/ # Accuracy graphs and model outputs ├── README.md # Project description └── requirements.txt # Required Python libraries

## 💻 How to Run

1. Clone the repository  
git clone https://github.com/yourusername/signature-forgery-verification.git
2. Install the required libraries  
pip install -r requirements.txt
3. Launch the application  
python gui_app.py
4. Upload a signature image and get a result: **Genuine** or **Forged**

## 📌 Future Enhancements

- Integrate with online signature verification
- Deploy as a web application
- Use ensemble learning for improved accuracy
- Add multilingual signature support

## 📄 License

This project is licensed under the MIT License.

---

*Developed as part of a mini project for academic purposes.*
