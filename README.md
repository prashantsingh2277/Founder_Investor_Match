# **Investor-Founder Match AI Model**  

This project aims to develop an AI model that evaluates the compatibility between startup founders and investors based on structured data. It leverages the **Gemini API** for fine-tuning a model that predicts a **match score** between investors and founders.

---

## **Project Overview**  

### **Objective**  
The AI model takes structured data containing:  
- **Founder Information**: Industry, startup stage, funding required, traction, and business model.  
- **Investor Preferences**: Preferred industry, investment range, and other criteria.  

Using this data, the model predicts a **match score** indicating how well an investor aligns with a startup.

---

## **How It Works**  

1. **Data Preparation**  
   - The dataset contains structured information about founders and investors.
   - The data is preprocessed into a format compatible with the **Gemini API**.

2. **Fine-Tuning the Gemini Model**  
   - The model is trained on the preprocessed data using the Gemini API.
   - It learns to assign a **match score** based on investor preferences and founder profiles.

3. **Generating Predictions**  
   - The trained model evaluates new founder-investor pairs.
   - It returns a ranked list of investors along with a compatibility score.

---

# 🚀 LLM-Powered Pitch Analysis Model

## 📌 Overview
This project implements an **AI-powered pitch deck evaluation model** using **Google Gemini API**. It **analyzes startup pitch decks** and provides:
- **A pitch score (0-100)**
- **Strengths & weaknesses of the pitch**
- **Suggested improvements**

## 📂 Features
✅ Extracts text from **PDF pitch decks**  
✅ Uses **LLM (Gemini API)** for **evaluation**  
✅ Assigns a **pitch score (0-100)**  
✅ Provides **strengths, weaknesses & improvement suggestions**  
✅ Saves results in **JSON & PDF report format**  
