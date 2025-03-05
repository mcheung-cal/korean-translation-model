# 🌏 NLP Model for Korean-English Translation with Formality Adaptation

## Collaborators: Eliot Arntz, Richard Zhang, Michelle Cheung

## 📝 Description  
This project develops an advanced **Natural Language Processing (NLP) model** for translating between **Korean and English**, with a focus on handling **formality levels** in Korean. By fine-tuning **LLaMa 2-7B** with **Parameter-Efficient Fine-Tuning (PEFT) and Quantized Low-Rank Adaptation (qLoRA)**, the model improves translation accuracy and contextual understanding of Korean honorifics and politeness levels.

## 💡 Key Features  
- ✅ **Translates Korean to English** while preserving **formality levels**  
- ✅ **Fine-tuned LLaMa 2-7B** using **PEFT with qLoRA** for efficient adaptation  
- ✅ **Incorporates formality tags** (Formal High, Formal Medium, Informal) in training data  
- ✅ **Evaluated with BLEU, ROUGE, BERT, and COMET scores** for translation quality  

## 🛠️ Built with  
- **Python**  
- **Hugging Face Transformers**  
- **PyTorch**  
- **LLaMa 2-7B Model**  
- **PEFT + qLoRA for fine-tuning**  
- **OPUS-100 Dataset (Helsinki-NLP)**  

## 📂 Dataset  
- **Sourced from OPUS-100**: English-centric multilingual corpus  
- **Preprocessed**: 300,000 sentence pairs with labeled formality levels  
- **Formality Tags**:  
  - **Formal High** (니다)  
  - **Formal Medium** (요)  
  - **Informal** (다 / 어)  

📌 **Findings**: The **fine-tuned model with formality levels** improves human-judgment-aligned translation (**higher COMET scores**) while maintaining high **semantic similarity (BERT scores)**.

## 🔗 Project Report & Code  
- [Final Report](https://github.com/mcheung-cal/korean-translation-model/blob/master/Korean_Translation_Report.pdf)  
- [Code Repository](https://github.com/mcheung-cal/korean-translation-model/blob/master/Korean_Translation_Final.ipynb)  

---

### 🚀 Future Directions  
- **Expand formality levels** to include more granular honorifics  
- **Increase dataset size** by labeling additional sentences  
- **Optimize fine-tuning process** for efficiency on larger models  

This project contributes to **culturally aware machine translation**, ensuring that translations maintain proper **tone, respect, and politeness** in diverse contexts.  
