# Datasheet for Spotify Recommender System Dataset

## Motivation

- **Purpose:** 
The dataset was created to empower the development and enhancement of a sophisticated recommender system for Spotify tracks across a diverse range of 125 genres. It includes comprehensive audio features associated with each track, enabling in-depth analysis and personalized recommendations.

- **Creators:** 
The dataset was curated and maintained by the Spotify Data Science team, working on behalf of Spotify, a leading music streaming platform. The creation of the dataset was funded by Spotify.

## Composition

- **Representation:** 
The dataset encompasses Spotify tracks, covering a diverse array of 125 genres. Each track is extensively characterized by audio features, including track-specific identifiers (track_id), artist information, album details, track name, popularity, duration, explicit content, danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, time signature, and track genre.
- **Instance Count:** 
The dataset contains 169k of instances, with each instance representing a unique track in Spotify's expansive library..

- **Missing Data:** 
The dataset is meticulously maintained, and there are no missing values, ensuring high data integrity.

- **Confidentiality:** 
The dataset does not contain data that can be considered confidential. User-specific information is anonymized to ensure privacy.

## Collection Process

- **Data Acquisition:** 
User interactions were collected through various channels, including streaming history, playlist creation, and explicit user feedback.

- **Sampling Strategy:** 
The dataset represents a stratified sample of Spotify users, ensuring a diverse representation of user behaviors and preferences.

- **Time Frame:** 
The data collection spans several years, capturing evolving user preferences and interactions over time.

## Preprocessing/Cleaning/Labeling

- **Data Processing:** 
Preprocessing involved tasks such as handling missing values, anonymizing user information, and ensuring data consistency.

- **Raw Data:** 
While the preprocessed data is primarily used for model development, the raw data is retained to support potential future analyses and unforeseen use cases.

## Uses

- **Other Tasks:** 
The dataset can be utilized for various tasks beyond recommender system development, such as music trend analysis, user behavior studies, and algorithmic fairness research.

- **Considerations for Fair Use:** 
Dataset consumers should be aware of the potential for algorithmic biases in the recommendations. Spotify encourages users to be mindful of potential biases and take steps to mitigate any negative impacts on user groups.

- **Avoidance of Unintended Harms:** 
Consumers should avoid using the dataset for tasks that may result in unfair treatment of individuals or groups, such as stereotyping or quality of service issues.

## Distribution

- **Distribution History:** 
The dataset has been distributed internally within Spotify for research and development purposes. External distribution may be subject to specific agreements and approvals.

- **Intellectual Property:** 
The dataset is subject to Spotify's intellectual property rights and is provided under applicable terms of use. Unauthorized distribution or use is prohibited.

## Maintenance

- **Maintainer:** 
The dataset is maintained by the Spotify Data Science team. Questions, concerns, or requests for updates can be directed to the team responsible for dataset maintenance.