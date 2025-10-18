# Stock-Market-Sentiment-Analysis-Using-NLP-Transformers
Developed an AI-driven sentiment analysis system that analyzes stock-related news articles to determine market sentiment (Positive, Negative, Neutral) and supports financial analysts in predicting stock price movements. Integrated deep learning-based sentence embeddings for accurate sentiment detection.

Tools & Technologies Used :-

Languages & Libraries: Python, NumPy, Pandas, Matplotlib, Seaborn, NLTK, Scikit-learn
NLP & Embeddings: Word2Vec, GloVe, Sentence Transformers (all-MiniLM-L6-v2)

Deep Learning Model: GPT-Neo (EleutherAI/gpt-neo-1.3B)

Platform: Google Colab, Hugging Face Transformers

Steps / Workflow :-
Imported and cleaned NASDAQ stock news data (with Open, Close, Volume, Sentiment labels).
Performed EDA (distribution plots, boxplots, and sentiment trends).
Implemented three text vectorization techniques — Word2Vec, GloVe, and Sentence Transformers.
Trained Logistic Regression models on embeddings and compared their accuracy and F1-scores.
Used Sentence Transformer embeddings as the best-performing model (Accuracy: 0.57).
Applied GPT-Neo for weekly summarization to extract top 3 positive and negative stock-impacting events.

Results / Output :-
Best Model: Sentence Transformer
Accuracy: 57%
F1-macro avg: 0.49
Captured balanced sentiment classification across Positive, Neutral, and Negative classes.
(Include image links if available, e.g., EDA charts or classification reports)

Conclusion / Insights :-

Sentence Transformer provided superior results compared to Word2Vec and GloVe.
LLM-based summarization (GPT-Neo) demonstrated potential for automated weekly stock sentiment reporting, enabling smarter financial decisions.
