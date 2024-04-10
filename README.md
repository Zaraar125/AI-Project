# Multi-Modal Meme Classification

## Project Overview
This project aims to classify memes into three categories: Positive, Negative, or Neutral. The classification is based on both the textual content and the image features of the memes. We leverage a custom neural network architecture that processes text and image data separately before combining them into a single layer within the network for classification.

## Text Feature Exraction
The textual features of the images were already made avaliable in the CSV file. Then further embeddings were extracted from those sentences using Sentence Transformers. These sentence transformers were quite powerful and extracted quite useful information from the textual data of images.

## Image Feature Extraction
The feautures of the images were simply resizing the images and normalizing the images.

## Custom Neural Network
A custom Neural Network was implemented in-order to classify the Memes into 3 categories. The Neural Network Consister of 5-Layers. The first 2 Layers of the Neural Network were basically disconnected from eachother. One of them accpted Imag Features and the other layer accepted Text Features. After from the Disconnected 2 layers, the Third layer bassically connected the outputs of the Disconncted layers into 1 single layer. This part merged the extracted features from both text and images into 1 layer. Then after further 2 layers, the Meme was being classified.

## Dataset Link: 
https://drive.google.com/file/d/1BW0DKYWtDdPMoVjuuCJ_E8TMDzSxjASb/view?usp=sharing
