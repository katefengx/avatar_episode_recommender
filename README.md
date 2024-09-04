# Avatar the Last Airbender: Recommending Episodes Based Off Emotions

This project is an episode recommender system that leverages the DistilRoBERTa-base emotion model to analyze and categorize emotions in the dialogue of Avatar the Last Airbender scripts. The system processes each line of the script, assigning emotion categories and calculating corresponding emotion scores. These scores represent the emotional tone of each episode.

To recommend episodes, the project uses Euclidean distance to measure the similarity between the emotion scores of different episodes. By comparing the emotional profiles, the system can suggest episodes with similar emotional content to the ones a user prefers.

The dataset is from Kaggle: https://www.kaggle.com/datasets/ekrembayar/avatar-the-last-air-bender
