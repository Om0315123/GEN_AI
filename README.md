# 🔗GENERATIVE_AI NOTES WITH CODES
<img src="https://github.com/user-attachments/assets/3304f5d3-e18e-4c3c-bfc3-a1521e529910">

# HOW DOES AI WORK ?

❓WHAT IS GENERATIVE ARTIFICIAL INTELIGENCE ? <br>
➡️ Simply speaking , Gen AI is a system that creates new content (text, images, videos, etc.) based on prompts and large language models (LLMs).
<br>
<br>
❓What is LLM and how are they trained ? <br>
➡️ It’s a type of artificial intelligence trained on huge amounts of text (books, websites, articles, chats, etc.).
<br>
➡️Language models are a key part of AI that help computers understand and generate human language.
<br>
➡️LLMs are trained using natural language processing (NLP) techniques and can generate content through it. NLP is a branch of machine learning that teaches computers to understand, interpret, and generate human language.
<br>
<br>
Some popular LLMs include: <br>
- OpenAI's GPT-4 <br>
- Anthropic's Claude<br>
- Google's Gemini

# NLTK ( NATURAL LANGUAGE TOOLKIT )
 👉 NLTK (Natural Language Toolkit) specializes in NLP tasks such as text generation, spell check, and translation.
 <br>
 👉 Python comes with many libraries that make work with language models easier. One of the most used libraries for AI is the nltk library.
 ## let's set up our Python environment with the NLTK
  - Create a new .py Python file. <br>
  - Install the nltk and numpy libraries. <br>
    - Code to do so :<br>
    ```python
    pip install numpy nltk
 ## DIVE INTO CONCEPTS 
 - TOKENIZATION
    - Tokens are small units of data used to train gen AI models like ChatGPT and help them understand and generate language. This data may take the form of whole words, subwords, and other content.
    - The process of making raw data like text trainable for language models is known as tokenization.
- Tokens are essential for language models because they are the smallest units of meaning. By analyzing tokens, models can understand the structure and semantics of text.
- Example <br>
- ```python
  import nltk 
  sample_text = 'I am learning Generative AI'
  tokens = nltk.word_tokenize(sample_text.lower())
  print('Tokens:', tokens)
