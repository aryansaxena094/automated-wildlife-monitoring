# Automated Wildlife Monitoring

## Introduction
This project focuses on developing an automated system for monitoring wildlife in their natural habitats, crucial for conservation strategies. Leveraging camera traps and advanced machine learning techniques, we aim to ease the workload on conservationists by accurately identifying a broad range of species across diverse environments. This initiative not only seeks to minimize costs and reduce human error but also to enhance the protection and tracking of species populations and changes.

## High level description/presentation of the project
 - This project focuses on developing an automated system for monitoring wildlife in their natural habitats, crucial for conservation strategies. Leveraging camera traps and advanced machine learning techniques, we aim to ease the workload on conservationists by accurately identifying a broad range of species across diverse environments. This initiative not only seeks to minimize costs and reduce human error but also to enhance the protection and tracking of species populations and changes.
 - Our approach integrates three main architectures: VGG16, ResNet18, and GoogLeNet. Each is chosen for its unique advantages in processing and identifying features within our varied datasets. Through a combination of data preprocessing, feature extraction, and transfer learning, we aim to build models that are highly accurate and efficient in identifying wildlife. 
 
## Requirements                
•⁠  ⁠matplotlib      
•⁠  ⁠numpy               
•⁠  ⁠sklearn             
•⁠  ⁠torch              
•⁠  ⁠torchvision         
•⁠  ⁠cuda                
•⁠  ⁠shutil 
•⁠  ⁠seaborn
•⁠  ⁠tensorboard        
•⁠  ⁠time    

## Instruction on how to train/validate the model
•⁠  ⁠To train and validate the model, we have created multiple .ipynb files for each dataset and each model. The models are saved in the respective folders.
•⁠  ⁠To train the model, change the location of the dataset in the code or link the kaggle account in your .ipynb files. The dataset for some models need to be loaded into kaggle as they required to be pruned. Run all the blocks under the training section.

## Instructions on how to run the test sample on the pretrained model
•⁠  ⁠User can also run the validation models by running the blocks under validation section in the .ipynb files. Dataloader should be preloaded with the test dataset. The validation accuracy, precision, recall and f1 score would be printed and T-SNE plots would be generated.


## Datasets
We utilize three distinct datasets, encompassing a range of classes and image sizes to support our objective:
- [**Dataset 1:** (10 Classes)](https://www.kaggle.com/datasets/alessiocorrado99/animals10) images across 30 classes (1024x683 resolution)
- [**Dataset 2:** (20 Classes)](https://www.kaggle.com/datasets/iamsouravbanerjee/animal-image-dataset-90-different-animals) 
3,570 images across 75 classes (224x224 resolution)
- [**Dataset 3:** (30 Classes)](https://www.kaggle.com/datasets/asaniczka/mammals-image-classification-dataset-45-animals)
 across 50 classes (1200x1200 resolution)

These datasets provide a robust foundation for training our models, catering to the varying complexities and scales essential for the project's success.

## Methodologies
Our approach integrates three main architectures: VGG16, ResNet18, and GoogLeNet. Each is chosen for its unique advantages in processing and identifying features within our varied datasets. Through a combination of data preprocessing, feature extraction, and transfer learning, we aim to build models that are highly accurate and efficient in identifying wildlife.


### Link to Our Github Page
•⁠  ⁠[Github Page](https://github.com/aryansaxena094/COMP6721-GroupH)

### Link to presentation
•⁠  ⁠[Presentation](https://drive.google.com/file/d/1bOpxsvVEDQudKzSqLb6Qoga63ngG2OCC/view?usp=drivesdk)
