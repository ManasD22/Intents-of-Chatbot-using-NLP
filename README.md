

## Overview  
This project introduces an intelligent chatbot designed to process and respond to user input using Natural Language Processing (NLP). The chatbot identifies user intents and delivers accurate responses based on a structured set of patterns and replies. It integrates popular libraries like `nltk` for NLP tasks, `scikit-learn` for machine learning, and `streamlit` for a user-friendly web interface.

---

## Key Features  
- Recognizes user intents such as greetings, farewells, and expressions of gratitude.  
- Provides meaningful and context-aware responses.  
- Tracks and saves the conversation history, allowing users to review previous interactions.  
- Built entirely with Python, leveraging state-of-the-art tools for NLP and machine learning.  

---

## Technology Stack  
- **Python**  
- **NLTK** for language processing tasks.  
- **Scikit-learn** for implementing machine learning models.  
- **Streamlit** for developing the interactive web application.  
- **JSON** for storing and managing chatbot intents.

---

## Installation Guide  

### Step 1: Clone the Repository  
Clone the project to your local machine using the following command:  
```bash  
git clone <repository-url>  
cd <repository-directory>  
```  

### Step 2: Set Up a Virtual Environment (Optional)  
It is recommended to create a virtual environment to manage dependencies:  
```bash  
python -m venv venv  
source venv/bin/activate  # For Windows, use `venv\Scripts\activate`  
```  

### Step 3: Install Dependencies  
Install the required libraries using the provided `requirements.txt` file:  
```bash  
pip install -r requirements.txt  
```  

### Step 4: Download NLTK Data  
Ensure you download the necessary data for `nltk`:  
```python  
import nltk  
nltk.download('punkt')  
```  

---

## Running the Application  
Launch the chatbot by running the following command in your terminal:  
```bash  
streamlit run app.py  
```  
Once the application is live, you can interact with the chatbot through the web interface. Simply type your message in the input field and press Enter to see the chatbot’s reply.  

---

## Customizing Intents  
The chatbot relies on an `intents.json` file to handle user queries. This file contains tags, patterns, and predefined responses. You can easily modify it to add new functionalities or update existing ones.  

---

## Conversation History  
The chatbot records all interactions in a CSV file (`chat_log.csv`). This allows users to review their previous conversations through the app's sidebar option.  

---

## Contributions  
Contributions are encouraged! If you have ideas for new features or enhancements, feel free to submit a pull request or open an issue.  

---

## License  
This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for more information.  

---

## Acknowledgments  
Special thanks to the following libraries and frameworks for making this project possible:  
- **NLTK** for enabling natural language processing.  
- **Scikit-learn** for machine learning tools.  
- **Streamlit** for providing an interactive platform to deploy the chatbot.  

---

You can replace `<repository-url>` and `<repository-directory>` with your specific details. Let me know if further adjustments are needed!
