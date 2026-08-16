# Aim and Research
This research aims to create an advanced deep learning system that can detect spoilage in fresh 
produce through pattern recognition in images. A primary objective of this study is to determine 
how accurately deep learning models can identify the various degrees of spoilage in fruit and 
vegetables. The study also examines the efficiency and accuracy of transfer learning models like 
ResNet18 and VGG16 alongside a custom CNN to determine the best approach. Furthermore, 
the impact of using Grad-CAM is measured in improving the interpretability of model outputs 
and strengthening the confidence in automated fruit and vegetable quality assessment. 


# Dataset and Exploratory Data Analysis (EDA)
I used a dataset called “Fruit Ripeness (Unripe, Ripe, Rotten)” that was acquired from Kaggle for 
implementing my model. There are a total of 34,158 training images and 7,778 test images split 
across nine classes, including freshbananas, rottenapples and unripeoranges. There are fewer 
images for categories like fresh bananas (9.26%), fresh apples (9.91%) and unripe oranges 
(8.58%) in the dataset. Some classes fall in a range such as rotten oranges (9.34%), unripe apples 
(11.84%) and unripe oranges (12.04%). We analyzed the distribution of data by creating bar and 
pie charts, standardized images using ImageNet statistics and created train, validation and test 
split using a 90:5:5 ratio. We also randomly selected images and compared them to ensure that 
all data was intact and that the applied data augmentation techniques had a positive impact. 
