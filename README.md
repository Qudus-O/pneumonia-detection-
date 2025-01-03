# Detect Pneumonia using X-ray Images with CNNs and Transfer Learning
[Pneumonia](https://www.healthline.com/health/pneumonia) is an infection caused by bacteria, viruses, or fungi. It leads to inflammation in the air sacs of one or both lungs. These sacs, called alveoli, fill with fluid or pus, making it difficult to breathe.

According to the [World Health Organization (WHO)](https://www.who.int/health-topics/pneumonia#tab=tab_1),Pneumonia killed more than 808 000 children under the age of 5 in 2017, accounting for 15% of all deaths of children under 5 years. People at-risk for pneumonia also include adults over the age of 65 and people with preexisting health problems.

In this project, we will taking the role of a Deep Learning Engineer for an R&D company that focusses on developing cuuting edge technologies to assist hospitals in diagnosing patients, particulary children.

## About the Dataset
Thanks to the researchers from the university of California, San Diego, the company has access to a dataset containing 5856 chest X-ray images from children, splits between a training set and a test dataset. Each Image has a label that specifies if the X-ray corresponds to a patient with pneumonia or one without it. The dataset can be downloaded [here](https://dsserver-prod-resources-1.s3.amazonaws.com/cnn/xray_dataset.tar.gz).

Our goal is to develop a deep learning model trained on these images that can accurately classify whether and x-ray indicates signs of pneumonia.

## Libraries
+ Pandas
+ Numpy
+ Tensorflow
