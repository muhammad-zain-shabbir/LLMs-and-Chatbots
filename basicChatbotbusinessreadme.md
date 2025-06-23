# 💬 Simple Business Chatbot

## 📌 Objective
This project implements a simple rule-based chatbot using Python and Gradio. It helps users get quick answers about a business’s:
- Pricing
- Services
- Contact information
- Working hours

The chatbot works without machine learning by combining **keyword matching** with **string similarity scoring** to determine the most relevant response.

---

## 🛠️ Tools & Libraries Used
- **Python 3**
- **Gradio**: For building a user-friendly chat interface
- **difflib (SequenceMatcher)**: For measuring string similarity
- `pandas`, `json`, `re`: For structured data and text handling

---

## 🧠 How It Works
The chatbot searches for matching answers based on:
- **Keyword hits** from the message
- **Similarity to example phrases**

Each intent (like “pricing” or “services”) has:
- A list of keywords
- Sample questions
- A response message

Scoring combines:
- 30% from keyword match count
- 70% from similarity to example questions

---

## 💡 Sample Questions
Try these in the chatbot:
- "How much does it cost?"
- "What services do you offer?"
- "How can I contact you?"
- "When are you open?"

---

## 🚀 How to Run the Chatbot

### 1. Install the Required Libraries
```bash
pip install gradio pandas
```

### 2. Run the Script
```bash
python chatbot.py
```

### 3. Open the Chatbot
Click the link displayed in the terminal to open the chatbot in your browser.  
You’ll see a textbox to enter your questions and responses will appear instantly.

---

## 🗂️ Project Files
```
├── chatbot.py       # Full chatbot source code
├── README.md        # This file
```

---

## 📈 Possible Improvements
- Add context or memory for multi-turn conversations
- Connect to live data/APIs for dynamic responses
- Introduce natural language processing (NLP) models for better accuracy
- Support for multiple languages

---

## 📬 Contact
For suggestions or questions, please reach out to:  
📧 **contact@business.com**

---

*Created with ❤️ using Python and Gradio.*
