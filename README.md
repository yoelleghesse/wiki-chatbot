This script utilizes the NLTK library for natural language processing, the WordNetLemmatizer for lemmatization, and the sklearn library for TF-IDF vectorization and cosine similarity calculation. It fetches content from a Wikipedia article (default: 'Vegetables') and processes user questions to find the most relevant sentence in the article that answers the question. If the cosine similarity between the user's question and the sentences in the article exceeds a certain threshold (0.3), the script returns the most relevant sentence as the answer.

Install dependencies:

``pip install nltk scikit-learn``

Download NLTK data:

``import nltk
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
nltk.download('punkt')``

Run the script:

``python wikipedia_qa_system.py``

Enter your questions when prompted. The system will attempt to provide answers based on the content extracted from the Wikipedia article.

To exit the system, type 'quit' when prompted for a question.
