# glaucoma-predictive-imaging

## Project for CS 4100

Glaucoma is a severe eye condition that leads to blindness without treatment. For our project, we make use of convolutional neural networks to predict glaucoma. Our goal is to craft a model capable of accurately identifying key features indicative of glaucoma from retinal images. Two approaches were attempted- a simple one-layer convolutional model and a MobileNetV3Large-enhanced model. While both models exhibit good performance in distinguishing unhealthy from healthy eyes, they struggle with classifying the "Glaucoma Suspected" label due to a lack of image sampling for that class. The MobileNetV3Large-enhanced model exhibits the greatest performance, which is understandable given the larger quantity of tunable parameters. Our results suggest that machine learning, coupled with fundus imaging can be used to assist medical professionals in glaucoma diagnosis. In the future, we could include segmentation models to improve feature detection and improve the model's ability to detect specific subsets of glaucoma.

### Files of Interest

Code: glaucoma-predictive-imaging.ipynb  
Retinal Images: full-fundus; Source: https://www.kaggle.com/datasets/deathtrooper/multichannel-glaucoma-benchmark-dataset/data  
Metadata (CSV file): metadata.csv; Source: https://www.kaggle.com/datasets/deathtrooper/multichannel-glaucoma-benchmark-dataset/data  
