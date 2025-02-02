### 📄 **Sentiment Analysis with BERT & XAI** Project  
---

## 📌 Description  
This project includes a Jupyter Notebook that performs **sentiment analysis** using the **BERT** model, while also leveraging **XAI (Explainable AI)** techniques to make the model's results more transparent and interpretable.  

🔹 **Key Features:**  
- Use of **BERT** for text sentiment analysis  
- Application of **XAI** techniques such as **LIME** and **SHAP** for model interpretability  
- **Visualization** of word impact on model predictions  
- Ability to train and evaluate the model on custom datasets  


---

## 🔧 Installation & Requirements 

### Dependencies  
**Libraries used in this project:**  
- `transformers`  
- `torch`  
- `numpy` and `pandas`  
- `lime` and `shap`  
- `matplotlib` and `seaborn`   

If any library is not installed on your system, you can install it using:  
```bash
pip install transformers torch numpy pandas lime shap matplotlib seaborn
```

### Run the Notebook  
```bash
jupyter notebook sentiment-analysis-bert-xai.ipynb
```
---

## 📊 How It Works  

1️⃣ **Load Data** 📥  
   - Text data for sentiment analysis is loaded.  

2️⃣ **Preprocess Data** 🔄  
   - Data is cleaned and prepared for the model.  

3️⃣ **Predict Sentiment with BERT** 🤖  
   - Input text is processed by the model, and its sentiment is identified.  

4️⃣ **Model Interpretability Analysis (XAI)** 🔍  
   - The impact of each word on the prediction is analyzed using XAI techniques like LIME and SHAP.  

---

## 📌 Sample Output  

✅ **Sentiment Prediction:**  
| Text | BERT Prediction |
|------|-----------------|
| "I love this product!" | Positive |
| "The service was terrible." | Negative |

✅ **Model Interpretability (LIME & SHAP):**  
📊 SHAP and LIME visualizations show which words had the most influence on the prediction.  

---

- If you have suggestions for improving the project, please submit a **Pull Request**.  
- To report issues, please open an **Issue**.  


