
# Product Recommendation System

In this project, a product recommendation system has been created on a local host using Python and deep learning. The system allows users to upload images, and the algorithm then generates and displays 5 recommendations from the dataset that match the uploaded image. CNN has been used in the creation of this project, and libraries and modules like ResNet50 and Tensorflow have been also heavily utilised. The proposed system demonstrates its ability to process an uploaded image, extract its features, compare those features to features already extracted from a large dataset, and then display the desired recommendations. For creating the web application streamlit framework has been used. Nearly all major e-commerce websites, including Amazon, Flipkart, Myntra, Walmart, etc., use this recommendation feature.






## Dataset

[Dataset Link](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset)

### System Requirements 
#### Hardware Requirements:

Minimum Hardware Requirements:  
Computer: Personal  
Processor: Pentium dual core       
RAM: 2gb      
Hard Disk Drive: 10 GB

Recommended Hardware Requirements:  
Computer: Personal  
Processor: Pentium quad core  
RAM: 4 GB  
Hard Disk Drive: 50 GB  
Solid State Drive: 50 GB  
Graphic Card: NVIDIA GeForce GT 710  

My Hardware Specifications:  
Computer: Personal  
Processor: Intel i5 9th gen Hexa core   
RAM: 8 GB  
Solid State Drive: 512 GB   
Graphic Card: NVIDIA GeForce GTX 1650  


### Software/Library’s Specific Version Requirements
Software/Library Required Version  
VS Code-- 1.XX.X   
Jupyter Notebook-- 6.4.XX   
Python-- 3.10.XX   
tensorflow-- 2.9.X   
keras-- 2.9.X







## Screenshots
### Sample Data
![Screenshot](https://drive.google.com/file/d/1CKvO4dd7RIFgWMESlig-tN1JbLs2Tr76/view?usp=share_link)
https://drive.google.com/file/d/1CKvO4dd7RIFgWMESlig-tN1JbLs2Tr76/view?usp=share_link

### Sample Output 

![Screenshot](https://drive.google.com/file/d/1CMaMMuT9snPR-Q37gyvw6ozw3-mQia50/view?usp=sharing)

https://drive.google.com/file/d/1CMaMMuT9snPR-Q37gyvw6ozw3-mQia50/view?usp=sharing


## Deployment

To deploy this project run

```VS Code Terminal
  streamlit run main.py (It will run on your local host)
```

### Note
After running codes of Feature Extraction.ipynb file two files will be generated automatically, named featurevector.pkl and filenames.pkl respectively (names could be anything you provide in the code).