# Model Card

See the [example Google model cards](https://modelcards.withgoogle.com/model-reports) for inspiration. 

## Model Description
The model analyzed in this card recommend songs based on user's preference. it recommend similar songs based on the genre of songs in the playlist

**Input:**
User's song list (listening history)
Spotify dataset containing song information
- Track features (e.g., artist, genre, album)

**Output:** 
Similar top 10 song recommendations for users based on their listening history and track features.

**Model Architecture:** 

The Spotify Recommender System utilizes cosine similarity to measure the similarity between the user's song preferences and songs in the Spotify dataset. Cosine similarity is calculated based on the scaled feature vectors of the songs. This approach captures the direction of the vectors, providing a measure of similarity that is robust to the scale of features.

## Performance

The model leverages cosine distances to recommend songs similar to those in the user's song list. Performance metrics, such as Mean Squared Error (MSE), Precision at K, and Recall at K, can be used to assess the accuracy and relevance of the recommendations. The current implementation assumes the availability of a pre-trained pipeline (song_cluster_pipeline) for scaling.

## Limitations

Cold Start Problem: New users with limited listening history may receive less accurate recommendations initially.
Niche Genres: Accuracy may decrease for users with preferences in niche or less popular music genres.
Data Imbalance: Recommendations may exhibit biases due to imbalances in the dataset, impacting underrepresented genres or artists.
Recommendations are based on existing song features and may not capture evolving user preferences.
## Trade-offs

Computational Resources: More accurate models may require increased computational resources.
Real-time Updates: Real-time model updates may introduce latency and impact user experience.
Sensitivity to User Interactions: Rapid changes in user preferences may temporarily affect the model's accuracy until the system adapts.

The model prioritizes simplicity and interpretability over complexity.
Recommendations may be influenced by biases present in the training data.
The performance relies on the quality and representativeness of the Spotify dataset.
