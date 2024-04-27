
# Product Recommendation System

In this project, a product recommendation system has been created on a local host using Python and deep learning. The system allows users to upload images, and the algorithm then generates and displays 5 recommendations from the dataset that match the uploaded image. CNN has been used in the creation of this project, and libraries and modules like ResNet50 and Tensorflow have been also heavily utilised. The proposed system demonstrates its ability to process an uploaded image, extract its features, compare those features to features already extracted from a large dataset, and then display the desired recommendations. For creating the web application streamlit framework has been used. Nearly all major e-commerce websites, including Amazon, Flipkart, Myntra, Walmart, etc., use this recommendation feature.



## Dataset

[Dataset Link](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)


### Software/Library’s Specific Version Requirements
Software/Library Required Version  
VS Code-- 1.XX.X   
Jupyter Notebook-- 6.4.XX   
Python-- 3.10.XX   
tensorflow-- 2.9.X   
keras-- 2.9.X


## Screenshots
### Sample Data
![Sample Data](https://github.com/AyushSingh012/Product-Recommendation-System/assets/109151442/82663abd-b343-4004-90ca-4756050802bb)


### Sample Output 
![Sample output](https://github.com/AyushSingh012/Product-Recommendation-System/assets/109151442/d76b549a-4263-4939-9151-68ed4d09c9af)


## Deployment

To deploy this project run

```VS Code Terminal
  streamlit run main.py (It will run on your local host)
```

### Note
After running codes of Feature Extraction.ipynb file two files will be generated automatically, named featurevector.pkl and filenames.pkl respectively (names could be anything you provide in the code).
