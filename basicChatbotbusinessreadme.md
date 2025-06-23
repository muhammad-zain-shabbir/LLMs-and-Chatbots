# 💬 Ordinary Business Simple Chatbot 

## 📌 Objective
This project implements a simple rule-based chatbot using Python and Gradio. It helps users get quick answers about a business’s:
- Pricing
- Services
- Contact information
- Working hours

The chatbot works without machine learning by combining **keyword matching** with **string similarity scoring** to determine the most relevant response.
You can think of this project as a much smaller version of BERT being used and it has a lot of room for improvement.

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
when you install the libraries, Please note that your code may not work so it is better for you to restart your Kernal if you're working on Jupyter Notebooks. 
It may take a few seconds to load for you because we are using free resources so please bear with it for a few seconds. 

### 2. Run the Script
```bash
basicChatbotbusiness.ipynb 
```

### 3. Open the Chatbot
Click the link displayed in the terminal to open the chatbot in your browser.  
You’ll see a textbox to enter your questions and responses will appear instantly.

---

## 🗂️ Project Files
```
├── basicChatbotbusiness.ipynb           # Full chatbot source code
├── basicChatbotbusinessreadme.md        # This file
├── basicChatbotbusinesspreview.png      # Preview of the Chatbot
├── README.md                            # Readme file for all similar projects

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
📧 **zainshabbir87@gmail.com**
   **(https://www.linkedin.com/in/muhammad-zain-shabbir-/)**

---

*Created with ❤️ using Python and Gradio.*
This is a very basic implementation for an idea that popped up for me as Ai is integrating at a massive scale in all industries, I wanted to make, test and see how customer-care and other fields would use the new emerging technologies and use them to make their work more efficient and accurate. I am not an expert so if you do find some flaws, Please go easy on me.
