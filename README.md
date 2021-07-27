# Image-Classification-Retrieval
Classify and Retrieve similar images of products using deep learning. 

#### Database
The dataset of E-commerce Product Images consisting of 100k labelled product images belonging
to 42 categories. Available at: https://www.kaggle.com/c/shopee-product-detection-open/data

#### Models used
- VGG-16 : Used to extract features, which are then used to classify images and also compare cosine similarity between the images.
- Siamese Neural Network with Contrastive loss : Used to compare the similarity between two images and retrieve the top 10 similar images to a given image.
