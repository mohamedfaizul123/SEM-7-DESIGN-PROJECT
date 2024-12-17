**Automatic Question Generator and Summarizer Using Machine Learning**

## **Overview**  
The *Automatic Question Generator and Summarizer Using Machine Learning* is a powerful tool that leverages Natural Language Processing (NLP) models to simplify and automate the generation of questions and summaries from textual data. By employing advanced machine learning techniques, this system is capable of processing large volumes of text, extracting key information, and producing relevant questions or concise summaries. It is particularly useful for educational purposes, content creators, and researchers who need automated solutions for comprehension and content review.

## **Motivation**  
The rapid increase in digital information has created a need for tools that can efficiently process, summarize, and generate meaningful content. Manually creating summaries or formulating questions from extensive documents is both time-consuming and labor-intensive. This project aims to address these challenges by providing an automated solution that reduces effort while maintaining accuracy and relevance. The motivation stems from improving learning efficiency, enabling content personalization, and supporting educators and learners alike.

## **Features**  
- **Automatic Question Generation:** Generate multiple-choice or short-answer questions based on input text.  
- **Summarization of Content:** Provides extractive or abstractive summaries for lengthy documents.  
- **Natural Language Processing (NLP):** Uses BERT or other transformer-based models to understand and process text.  
- **Customizable Output:** Allows users to configure the number of questions or summary length as per their requirements.  
- **User-Friendly Interface:** Simplified and intuitive user interface for ease of access.  
- **Batch Processing:** Supports processing of multiple files or documents simultaneously.  

## **How It Works**  
1. **Text Preprocessing:** Input text is cleaned, tokenized, and preprocessed to remove noise (e.g., special characters).  
2. **Summarization Module:**  
   - **Extractive Summarization:** Key sentences are selected directly from the text using NLP models.  
   - **Abstractive Summarization:** New sentences are generated to convey the essence of the input text.  
3. **Question Generation:**  
   - Machine learning algorithms analyze the input text and identify key concepts.  
   - Relevant questions are generated based on these key points, ensuring coherence and accuracy.  
4. **Model Deployment:** The system utilizes pre-trained transformer models (e.g., BERT) to generate output efficiently.  
5. **User Interaction:** Users can input text via a user-friendly interface, configure settings, and retrieve the results in seconds.  

## **Installation**  
To install and set up the system, follow these steps:  
1. **Clone the Repository:**  
   ```bash  
   git clone <repository_link>  
   cd automatic-question-summarizer  
   ```  
2. **Install Dependencies:**  
   Ensure Python is installed (>=3.8). Then run:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. **Download Pre-trained Models:**  
   Download the BERT or any other model from Hugging Face or TensorFlow Hub.  
   ```bash  
   # Example for Hugging Face  
   pip install transformers  
   ```  
4. **Run the Application:**  
   ```bash  
   python main.py  
   ```  

## **Usage**  
1. **Input Text:** Provide the input text file, URL, or raw content in the interface.  
2. **Select Options:** Choose between summarization, question generation, or both.  
3. **Configure Settings:** Set the summary length, number of questions, and type of questions.  
4. **Generate Output:** The system processes the input and produces results.  
5. **View/Export Results:** Retrieve the generated summary or questions and export them as a text or PDF file.  
