# Machine-Learning-roach-for-Brain-Tumor-Detection

In this project, I used Opencv and machine learning technique to detect tumour and segment the tumour part from the image.

I took data from [Kaggle](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection),

This Image contains the tumour and we need to extract it.

![cap1](https://user-images.githubusercontent.com/39022530/77041118-4e452800-69df-11ea-9580-509c51542a16.PNG)&

Step 1)
we will threshold the image:

![cap2](https://user-images.githubusercontent.com/39022530/77041749-784b1a00-69e0-11ea-864b-3e3199764989.PNG)&

Step 2)
we will erode image to remove the all noise from the image:

![cap3](https://user-images.githubusercontent.com/39022530/77042023-fb6c7000-69e0-11ea-83e2-879551d648f7.PNG)&


Step 3)
we will dilate image to increase the region of interest:

![cap4](https://user-images.githubusercontent.com/39022530/77041980-e4c61900-69e0-11ea-8fa7-942972b99b59.PNG)&


Step 4)
extract the brain from image

![cap5](https://user-images.githubusercontent.com/39022530/77042085-1939d500-69e1-11ea-8a51-2ec926cd5d44.PNG)&


Step 5)
extract the tumour part from the image:

![cap7](https://user-images.githubusercontent.com/39022530/77042136-2eaeff00-69e1-11ea-804f-88109d9c5e84.PNG)&



Step 6) Map the tumour part to the image:

![cap8](https://user-images.githubusercontent.com/39022530/77042211-4d14fa80-69e1-11ea-894f-ef823fa08f54.PNG)&

