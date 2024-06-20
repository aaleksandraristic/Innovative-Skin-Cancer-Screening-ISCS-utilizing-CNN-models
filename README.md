# Innovative Skin Cancer Screening (ISCS) Using Deep Learning 

The goal of this project is to employ an intelligent system for the identification of abnormalities by analyzing images of the skin tissues. The focus will be on leveraging advanced algorithms and deep learning techniques to analyze images and train the model to identify if the image of the skin is showing malignant or benignant cancer. 

# Dataset: 

- 10015 dermatoscopic images
- a variety of diagnostic categories of pigmented lesions:
● Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec)
● Basal cell carcinoma (bcc)
● Benign keratosis-like lesions (bkl)
● Dermatofibroma (df)
● Melanoma (mel)
● Melanocytic nevi (nv)
● Vascular lesions (vasc)

- CSV file contains details about our data points, as shown below:

![image](https://github.com/aaleksandraristic/Innovative-Skin-Cancer-Screening-ISCS-utilizing-CNN-models/assets/140200824/5947b16f-8415-406a-990d-10896bcd2e61)

- compare images that we used - ‘bkl’ and ‘mel’, as shown below:

![image](https://github.com/aaleksandraristic/Innovative-Skin-Cancer-Screening-ISCS-utilizing-CNN-models/assets/140200824/cd26a4e5-b789-407e-8a3e-387f26d451fb)

- resource: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T

# Methods: 

1. **Residual Neural Network (ResNet50)** - Using ResNet50 for skin abnormality classification involves collecting a diverse dataset of skin abnormality images labeled with malignant or benign cancer,
preprocessing the images by resizing and normalizing them, and then leveraging transfer learning by fine-tuning the pre-trained ResNet50 model on the dataset. This
entails freezing the initial layers and retraining the later ones. Subsequently, the model is trained on the dataset to learn to extract relevant features and classify images
accurately. After evaluation on a separate dataset to measure performance metrics, such as accuracy and loss, the model can be deployed in real-world applications for
automatic classification of skin abnormalities based on their likelihood of being malignant or benign cancer.

2. **Densely Connected Convolutional Networks (DenseNet121)** - Offers a compelling combination of improved accuracy, parameter efficiency,
gradient flow, and interpretability, making it a popular choice for various computer vision tasks where deep learning models are deployed.

3. **GoogLeNet - InceptionV3** - At the heart of Inception lies its distinctive architecture, characterized by inception modules. These modules are pivotal components employing parallel convolutional pathways to
extract features across various scales concurrently. This approach enables the network to capture intricate details while maintaining computational efficiency.

# Results:
![image](https://github.com/aaleksandraristic/Innovative-Skin-Cancer-Screening-ISCS-utilizing-CNN-models/assets/140200824/6d05b8a1-10e4-4d37-9191-2475980d492d)

![image](https://github.com/aaleksandraristic/Innovative-Skin-Cancer-Screening-ISCS-utilizing-CNN-models/assets/140200824/d1b04a4e-cdde-4b81-afe4-0cc0042423e0)


# Conclusion: 

Upon analysis of the results, it was found that InceptionV3 emerged as the top-performing model for skin image recognition. Its architecture, which incorporates sophisticated convolutional neural networks, proved effective in capturing intricate features present in skin images, leading to more accurate classification results. While InceptionV3 showed promising performance, there are opportunities for further improvement. Future adjustments could involve fine-tuning the model hyperparameters, such as learning rate, batch size, and optimizer choice, to enhance accuracy and convergence speed potentially. Additionally, data augmentation techniques could be employed to increase the diversity and quantity of training data, thereby improving the model's ability to generalize to unseen skin images. In conclusion, this project underscores the importance of selecting appropriate deep-learning models for specific image recognition tasks. While InceptionV3 emerged as the best-performing model in this context, ongoing research and experimentation are essential to continually refine and optimize skin image recognition systems, ultimately contributing to advancements in medical diagnostics and patient care.


[Intelligent Skin Cancer Screening (ISCS) - Final Report.pdf](https://github.com/user-attachments/files/15909776/Intelligent.Skin.Cancer.Screening.ISCS.-.Final.Report.pdf)
