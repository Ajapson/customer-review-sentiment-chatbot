# Product Review Sentiment + Reasoning

## Business Name
E-Commerce Feedback Intelligence System

## Project Overview
This project provides an automated solution for analyzing customer reviews in an e-commerce platform. 
The application classifies the sentiment of each review (Positive, Neutral, Negative) and uses a Large Language Model (LLM) 
to generate explanations for the detected sentiment. For negative reviews, the system provides reasoning behind the 
customer dissatisfaction and offers a feature to rephrase the review in a neutral or brand-friendly tone. 
The system also supports exporting the results to an internal ticketing system.

This tool is aimed at helping the e-commerce feedback team quickly identify critical issues, 
understand emotional drivers behind feedback, and respond effectively to customers.

---

## Key Features
- **Sentiment Classification**: Automatically categorize reviews as Positive, Neutral, or Negative.
- **LLM-Generated Reasoning**: Explain why a review was classified in a certain way.
- **Rephrase Capability**: Transform a review into a neutral or brand-friendly tone.
- **Export/Copy Function**: Easily export results or copy to the clipboard for internal workflows.
- **Web Interface**: User-friendly interface for entering reviews and viewing results.
- **Cloud-Hosted**: Accessible from anywhere via a cloud deployment.

---

## Technology Stack
- **Programming Language**: Python
- **Framework**: Streamlit (for the web interface)
- **AI/ML Models**:
  - Sentiment analysis: Pre-trained model (e.g., Hugging Face pipeline or OpenAI sentiment endpoint)
  - Text generation and reasoning: LLM (e.g., OpenAI GPT-4 or similar)
- **Hosting**: Streamlit Cloud / Hugging Face Spaces / Google Cloud
- **Libraries**:
  - Transformers
  - Streamlit
  - Requests / OpenAI API
  - Pandas / Numpy

---

## System Architecture
1. **User Input**: The user enters a product review in the text area of the web app.
2. **Sentiment Analysis**: The system classifies the review sentiment.
3. **Reasoning Generation**: The LLM generates a detailed explanation of the sentiment classification.
4. **Rephrasing**: If required, the system rephrases the review into a neutral tone.
5. **Export/Copy**: The output can be exported or copied to an internal ticketing system.

---

## How to Run Locally

### Prerequisites
- Python 3.9 or later
- API key for OpenAI or Hugging Face
- Git installed on your system

### Installation
```bash
# Clone the repository
git clone <YOUR_GITHUB_REPO_LINK>
cd <YOUR_REPO_NAME>

# Install dependencies
pip install -r requirements.txt
```

### Run the Application
```bash
streamlit run app.py
```

---

## Cloud Deployment
The application is deployed on the cloud for easy access:
- **UI Link (A1)**: https://4a0b95d94c15db35a1.gradio.live/
- **Business Application (A2)**: Integrated with UI
- **Cloud Hosted Link (A3)**: https://huggingface.co/spaces/Ajapson/product-review-sentiment

---

## Embedded AI Features
1. **Sentiment Classification**
   - Uses NLP sentiment analysis models to detect positive, neutral, or negative tone.
2. **LLM Reasoning**
   - Calls the LLM API to explain the detected sentiment.
3. **Rephrase Functionality**
   - Uses the LLM to rewrite negative reviews in a brand-friendly tone.
4. **Integration**
   - AI is embedded within the Streamlit UI, so all features are available in one interface.

---

## Example Usage
1. Open the web app.
2. Paste a customer review.
3. View sentiment classification and reasoning.
4. Optionally rephrase and export.

---

## Author
Developed by: Osen Ajape Damilola
