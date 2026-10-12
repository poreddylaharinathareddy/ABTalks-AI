# ABTalks AI Challenge - Day 1

## How a Chatbot Works

A chatbot receives a question or message from the user as input.
It processes the input using an AI model that understands the user's request.
The AI model uses patterns learned from data to generate a suitable response.
The generated response is then sent back to the user as output.
This process can be represented as Input → Processing → Output.

---

# Day 2 — Your First Python AI Script 🐍

## What I Learned

Today I worked with Python and Google Colab to understand basic text processing.

## Tasks Completed

- Set up a Google Colab notebook and ran my first Python cell.
- Created a Python script to count word frequency in a sentence.
- Created a text-cleaning script to convert text to lowercase.
- Removed punctuation and normalized whitespace.

## Notebook

The complete working notebook is available in:

`ABTalks_AI_Day2.ipynb`

## Key Takeaway

Small Python programs can be used to process and clean text, which forms a basic foundation for working with AI and Natural Language Processing.


## Day 3 — Text is Data: Turning Words into Numbers 🔢

Today I learned how raw text can be transformed into a format that machine learning models can work with.

### What I Learned

- Tokenization using NLTK
- Removing stop words
- Removing punctuation
- Converting text to lowercase
- Creating a Bag-of-Words representation
- Preparing processed text as ML-ready input

### Tasks Completed

✅ Tokenized a sample paragraph using NLTK  
✅ Removed English stop words  
✅ Removed punctuation  
✅ Converted tokens to lowercase  
✅ Created a Bag-of-Words representation using word frequencies  
✅ Created a preprocessed text dataset ready for ML input  

### Notebook

📓 [ABTalks AI Day 3 Notebook](Day-3/ABTalks_AI_Day3.ipynb)

### Key Takeaway

Text needs to be cleaned and converted into numerical representations before a machine learning model can process it. Tokenization, preprocessing, and Bag-of-Words are basic but important steps in Natural Language Processing (NLP).

**Day 3 complete! 🚀**


## Day 4 — Vectors: Teaching Meaning to Machines 🧠

### What I Learned
Today, I explored how AI represents sentences as numerical vectors called **embeddings** and compares their meanings using cosine similarity.

### Tasks Completed
- Installed and imported the `sentence-transformers` library in Google Colab.
- Generated embeddings for five sentences with similar and different meanings.
- Compared sentence pairs using cosine similarity.
- Observed how similarity scores help identify sentences with related meanings.
- Wrote a reflection on what I learned.

### Key Takeaway
I learned that sentences with similar meanings can have high similarity scores even when they use different words. Embeddings are useful in semantic search, recommendation systems, chatbots, and Retrieval-Augmented Generation (RAG).

### Notebook
[ABTalks_AI_Day4.ipynb](Day-4/ABTalks_AI_Day4.ipynb)


---

## Day 5 — Build a Mini Search Engine 🔎

### Objective
Build a mini semantic search engine that finds sentences based on meaning rather than only matching keywords.

### What I Learned
- Sentence embeddings using Sentence Transformers
- Vector representations of text
- Cosine similarity for comparing sentence meanings
- Semantic search vs. keyword search

### Tasks Completed
- Created a dataset containing 20 sentences
- Converted sentences into numerical embeddings using `all-MiniLM-L6-v2`
- Built a Python semantic search function
- Retrieved the top 3 most similar sentences for a query
- Compared semantic search with keyword search
- Tested the search engine with different queries

### Technologies Used
- Python
- Google Colab
- Sentence Transformers
- Scikit-learn
- NumPy

### Notebook
[`ABTalks_AI_Day5.ipynb`](Day-5/ABTalks_AI_Day5.ipynb)

### Key Takeaway
Semantic search helps computers find information based on meaning, even when the exact words differ. It is useful for AI chatbots, semantic retrieval, and Retrieval-Augmented Generation (RAG).

**Day 5 completed! 🚀**
