# Chat_Bot_QA, Question & Answer System Based on Google Palm LLM and Langchain for E-learning company.

This is an end-to-end LLM project based on Google Palm and Langchain. We are building a Q&A system for an e-learning company. The company sells data-related courses and boot camps. They have thousands of learners who use Discord server or email to ask questions. This system will provide a streamlit-based user interface for students where they can ask questions and get answers.
# Project Highlights
Use a real CSV file of FAQs that Codebasics company is using right now.
Their human staff will use this file to assist their course learners.
We will build an LLM-based question-and-answer system that can reduce the workload of their human staff.
Students should be able to use this system to ask questions directly and get answers within seconds

# Learning from Project
Langchain + Google Palm: LLM based Q&A
Streamlit: UI
Huggingface instructor embeddings: Text embeddings
FAISS: Vector database

# Installation
    cd 3_project_codebasics_q_and_a
    pip install -r requirements.txt
    GOOGLE_API_KEY="your_api_key_here"

# Usage
1) Run the Streamlit app by executing:
streamlit run main.py
The web app will open in your browser.

2) To create a knowledebase of FAQs, click on Create Knolwedge Base button. It will take some time before knowledgebase is created so please wait.

Once knowledge base is created you will see a directory called faiss_index in your current folder

Now you are ready to ask questions. Type your question in Question box and hit Enter

# Project Structure
main.py: The main Streamlit application script.
langchain_helper.py: This has all the langchain code
requirements.txt: A list of required Python packages for the project.
.env: Configuration file for storing your Google API key.
