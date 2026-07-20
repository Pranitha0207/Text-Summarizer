# Text-Summarizer
Text Summarizer Decision Advisor is an interactive Streamlit-based application that helps users choose the most suitable text summarization technique based on their hardware environment and primary requirements. The system compares extractive summarization using LSA (Sumy) with abstractive summarization using the BART Transformer model.

The application uses a scoring-based decision engine to recommend the best summarization approach according to factors such as execution speed, cost, factual accuracy, and human-like readability. Users can then enter long text and generate a summary using the recommended algorithm. NLTK is used for text tokenization, while Hugging Face Transformers provides the BART model for abstractive summarization. Streamlit caching is also implemented to improve performance by loading the machine learning model only once.

Overall, the project provides a simple and intelligent way to select and test summarization algorithms according to user constraints and requirements.
