# Transformers_Movie_reviews

Here I first did EDA on movie reviews data

Then made a model for semantic search using *all-MiniLM-L6-v2* model from hugging face. Here I first converted the given dataset into vector embeddings. Then I made a function to calculate cosine similarity between two sentences. If two sentences have high cosine similarity score that indicates that the sentences are semantically similar. Then I made a function to find top k similar reviews . In this when i enter my embedded matrix and my query text , it would return me top k reviews similar to that query.

Then made a model for sentiment analysis. First I used random forest model on embedded matrix. Then I used pre trained model from hugging face "sentiment-analysis" pipeline. 
