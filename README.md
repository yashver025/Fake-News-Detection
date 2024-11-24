# Fake-News-Detection

## **Overview**  
This project aims to classify news articles as **reliable** or **unreliable** using machine learning and natural language processing (NLP). It preprocesses text data, extracts features using TF-IDF, and leverages a trained model to make predictions. A user-friendly interface is provided via a Streamlit app.

---

## **Features**  
- Text preprocessing: Noise removal, tokenization, stopword elimination, and stemming.  
- Feature extraction using **TF-IDF Vectorizer** for numerical representation of text.  
- Classification of news articles using a pre-trained machine learning model.  
- Interactive web application for user input and real-time predictions.  

---

## **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**:  
  - **Streamlit**: Web interface  
  - **Scikit-learn**: Model training and evaluation  
  - **NLTK**: Text preprocessing  
  - **Pickle**: Model serialization  
- **Machine Learning Algorithm**: Logistic Regression / SVM  

---

## **Setup Instructions**  
### **1. Clone the Repository**  
```bash  
git clone https://github.com/your_username/fake-news-detection.git  
cd fake-news-detection  
```  

### **2. Install Dependencies**  
Ensure you have Python installed, then run:  
```bash  
pip install -r requirements.txt  
```  

### **3. Run the Application**  
Start the Streamlit app:  
```bash  
streamlit run app.py  
```  

### **4. Add Required Files**  
Ensure the following files are in the project directory:  
- `model.pkl`: Trained classification model.  
- `vector.pkl`: Pre-trained TF-IDF vectorizer.  

---

## **How It Works**  
1. **User Input**: Enter news content into the Streamlit interface.  
2. **Preprocessing**: Text is cleaned and transformed into numerical features.  
3. **Prediction**: The model classifies the content as "Reliable" or "Unreliable."  
4. **Output**: Results are displayed in the app.  

---

## **Future Enhancements**  
- Improve accuracy with advanced models like Transformers (BERT).  
- Add support for multiple languages.  
- Integrate with social media platforms for real-time detection.  

---

## **Contributing**  
Contributions are welcome! Please fork the repository and create a pull request for review.  

---
