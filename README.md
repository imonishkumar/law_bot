# 📚 **LawBot: AI-Powered Legal Assistant 🤖**

**LawBot** is a Python-based chatbot designed to answer legal queries intelligently. By leveraging Natural Language Processing (NLP) and a neural network, it simplifies legal interactions and provides accurate responses, making legal assistance accessible to all.

---

## 🚀 **Features**  
- **Legal Query Understanding**: Processes user inputs and provides context-aware answers.  
- **Customizable**: Easily add or update intents and responses in `intents.json`.  
- **Interactive Chat**: Engages in real-time conversations.  
- **Powered by AI**: Uses NLP and a trained neural network for precision and efficiency.

---

## 🛠️ **Project Structure**  

| **File/Folder**  | **Description**                                                                                   |  
|------------------|---------------------------------------------------------------------------------------------------|  
| `train.py`       | Trains the neural network using the data in `intents.json` and saves the trained model in `data.pth`.  |  
| `model.py`       | Defines the architecture of the neural network for classifying user inputs.                       |  
| `nltk_utils.py`  | Utility functions for text processing, including tokenization, stemming, and bag-of-words creation. |  
| `chat.py`        | Interactive chatbot that uses the trained model to respond to user queries.                       |  
| `intents.json`   | Stores predefined patterns (inputs) and responses for training and chat.                          |  
| `data.pth`       | Serialized file containing the trained neural network model.                                      |  

---

## 🔧 **How to Get Started**  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/imonishkumar/law_bot.git  
   cd law_bot  
   ```  

2. **Install Dependencies**  
   Ensure Python 3.x is installed, then run:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. **Train the Model**  
   Prepare the chatbot by training it with the provided intents:  
   ```bash  
   python train.py  
   ```  

4. **Start the Chat**  
   Interact with your personal legal assistant:  
   ```bash  
   python chat.py  
   ```  

---

## 📂 **Data Structure**  

- **`intents.json`**  
  This JSON file organizes the training data into:  
  - **Patterns**: Example user inputs.  
  - **Responses**: Possible bot replies.  
  - **Tags**: Labels for classification.  

```json  
{  
  "intents": [  
    {  
      "tag": "contract",  
      "patterns": ["What is a contract?", "Explain contract laws"],  
      "responses": ["A contract is a legally binding agreement...", "In legal terms, a contract refers to..."]  
    },  
    {  
      "tag": "divorce",  
      "patterns": ["How does divorce work?", "Tell me about divorce laws"],  
      "responses": ["Divorce laws vary by jurisdiction but typically involve...", "Divorce is a legal dissolution of marriage..."]  
    }  
  ]  
}  
```  

---

## ✨ **Customization**  
1. **Modify Intents**: Add new topics or update responses in `intents.json`.  
2. **Adjust Model**: Update the neural network in `model.py` for improved performance.  

---

## 📜 **Acknowledgments**  
- **Libraries Used**:  
  - [NLTK](https://www.nltk.org/) for text processing  
  - [PyTorch](https://pytorch.org/) for neural network implementation  

---

## 💡 **Future Improvements**  
- Add support for multiple languages.  
- Implement voice-based interactions.  
- Enhance model accuracy with larger datasets.  

---

## 📫 **Contact**  
If you have any questions, issues, or feedback regarding **LawBot**, feel free to reach out!  
📧 **Email**: [monishkumarpecai@gmail.com](mailto:monishkumarpecai@gmail.com)  

---

## 🛡️ **License**  
This project is licensed under the [MIT License](LICENSE).  

---

Feel free to contribute or report issues. Let's make legal assistance smarter and more accessible! monishkumarpecai@gmail.com 🎉  
