# Chat with a Website from URL - LangChain Chatbot with Streamlit GUI

Welcome to the LangChain Chatbot with Streamlit GUI GitHub repository! Here, you'll find a comprehensive guide on crafting a chatbot capable of seamlessly interacting with websites, extracting valuable information, and engaging users through a sleek Streamlit interface. This project harnesses the robust capabilities of LangChain 0.1.0, seamlessly integrating it with a user-friendly Streamlit GUI for a refined user experience.

🟡 This repository serves as supplementary material for an accompanying YouTube video tutorial.

**Key Features:**

Website Interaction: The chatbot utilizes the latest LangChain version to interact with diverse websites and extract pertinent information.

Integration with Large Language Models: This project is compatible with various models including GPT-4, Mistral, Llama2, and ollama. While the default is GPT-4, you have the flexibility to switch to any other model of your choice.

Streamlit GUI: Enjoy a clean and intuitive user interface crafted with Streamlit, catering to users with varying technical proficiencies.

Python-based Implementation: The entire project is meticulously coded in Python for simplicity and versatility.

**Understanding RAG:**

A RAG bot, or Retrieval-Augmented Generation bot, enhances the knowledge of our Language Model (LM) by incorporating additional information passed within the prompt. This involves vectorizing the desired text and identifying the most relevant information to augment the LM's understanding, thereby enriching its responses.

For a more detailed explanation, refer to the accompanying YouTube tutorial or the provided diagram illustrating the process.

**Installation:**

Ensure Python is installed on your system, then clone this repository:
```bash
git clone [repository-link]
cd [repository-directory]
```
Install the necessary packages:
```bash
pip install -r requirements.txt
```
Create a .env file with the following variables:
```plaintext
OPENAI_API_KEY=[your-openai-api-key]
```

**Usage:**

To launch the Streamlit app, execute:
```bash
streamlit run app.py
```

**Contributing:**

This repository is primarily intended as a companion to the YouTube tutorial; thus, I'm not accepting pull requests unless they address bugs or typos.

**License:**

The project is licensed under the MIT License. Refer to the LICENSE file for specifics.

**Note:**

This project is designed for educational and research purposes. Ensure compliance with the terms of use and guidelines of utilized APIs and services.

I trust this repository proves instrumental in your AI and chatbot development journey. For additional insights and tutorials, visit [Your YouTube Channel].

Happy Coding! 🚀👨‍💻🤖

If you find this repository helpful, don't forget to star it!
