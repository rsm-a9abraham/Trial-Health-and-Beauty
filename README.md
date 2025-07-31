The scored_dataset file is the original dataset with reviews but now contains aspect (durability, value, quality, etc.) scores and review sentiment scores. 
Missing prices were imputed after creating inferred categories (KMeans Clustering and Sentence Embeddings)
All the reviews were combined into one reviews for sentiment analysis. One product only has one total reveiw now (combination of all the reviews).
Durability, Quality, Functionality, Value, and Overall Sentiment scores were assigned using a hybrid model (transformer for overall sentiment scoring and sentiment hearistic for aspect scoring)
