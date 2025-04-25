# 🧠 MindEase – Your Mental Health Companion 🫂❤️

MindEase is an AI-powered mental health companion built with LangChain, Google Gemini, and Streamlit. It helps users express their thoughts and get supportive, empathetic responses using a large language model and contextual prompts.

---

## 🚀 Features

- Personalized mental health support powered by Google Gemini
- Context-aware responses based on embedded mental health data
- Beautiful, minimal Streamlit interface with custom CSS
- Session-based conversation history

---

## 🛠️ Getting Started

Follow these steps to set up and run the app locally.

### 1. **Clone the Repository**

```bash
git clone https://github.com/adi1174/AI_DA_ADITYA
.git
cd mindease
```
2. Set up a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
    
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    
4. Create a `.env` file in the root directory of the project and add your GEMINI API KEY:
    ```bash
    GOOGLE_API_KEY="your-api-key-here"
    ```

After setting up the project and installing dependencies, run the app with the following command:

```bash
streamlit run app.py
