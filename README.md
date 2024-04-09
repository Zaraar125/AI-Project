# Multi-Modal Meme Classification

## Project Overview
This project aims to classify memes into three categories: Positive, Negative, or Neutral. The classification is based on both the textual content and the image features of the memes. We leverage a custom neural network architecture that processes text and image data separately before combining them into a single layer within the network for classification.
## Project Approach
1. **Data Preprocessing**:
   - Clean and preprocess text data (remove stopwords, punctuation, etc.).
   - Normalize image features (resize, scale, etc.).
2. **Model Architecture**:
   - Design a custom neural network architecture.
   - Separate branches for processing text and image features.
   - Merge layer to combine features from both branches.
   - Classification layer for predicting meme sentiment.
3. **Training**:
   - Split the data into training, validation, and test sets.
   - Train the model using the training data.
   - Validate and fine-tune hyperparameters using the validation set.
4. **Evaluation**:
   - Evaluate the model's performance on the test set.
   - Measure metrics such as accuracy, precision, recall, and F1 score.
   - Analyze the model's ability to classify memes into the correct sentiment categories.
5. **Deployment**:
   - Once satisfied with the model's performance, deploy it for real-world classification tasks.
   - Integrate the model into an application or service for meme sentiment analysis.
## Usage
1. Clone the repository: 
## Dataset Link: https://drive.google.com/file/d/1BW0DKYWtDdPMoVjuuCJ_E8TMDzSxjASb/view?usp=sharing
