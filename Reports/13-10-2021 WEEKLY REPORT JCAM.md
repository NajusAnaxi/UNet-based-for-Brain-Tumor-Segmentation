# WEEKLY REPORT

# What I did this week?

1. Study chinese grammar.
2. Working with Mehrdad-Noori/Brain-Tumor-Segmentation (Python).
3. Working with sdsubhajitdas/Brain-Tumor-Segmentation.
4. How to use Google Colab.

# PROBLEMS

## Chinese Grammar

![](C:\Users\RA-IS\Pictures\Nueva carpeta\Imagen1.png)



## sdsubhajitdas/Brain-Tumor-Segmentation (Python)

1. Download the complete Dataset, and extract in Original Image and Original Mask (containing 3064 T1-weighted contrast-inhanced images
   from 233 patients with three kinds of brain tumor: meningioma (708 slices), glioma (1426 slices), and pituitary tumor (930 slices), with a total of 3064 images).

![image-20211013065043539](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013065043539.png)

2. Divide the images into 5 parts to train 4 and test with 1.

![image-20211013065242087](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013065242087.png)

![image-20211013065302272](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013065302272.png)

3. Train again the model (6 hours).

![image-20211013064913554](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013064913554.png)

![image-20211013142408274](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013142408274.png)

![image-20211013142434073](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013142434073.png)

#### Results

![image-20211013142455231](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013142455231.png)

![image-20211013142516747](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013142516747.png)

![image-20211013142539864](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013142539864.png)



![image-20211013142653660](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013142653660.png)

##  Mehrdad-Noori/Brain-Tumor-Segmentation

1. GPU doesn't work.

![image-20211013144658453](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013144658453.png)

![image-20211013145410257](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013145410257.png)

2. GPU doesn't have enough memory (Find that the problem was the batch_size).

![image-20211013145440083](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013145440083.png)

![image-20211013150045227](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013150045227.png)

3. GPU is not good to run the project.

![image-20211013150241912](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013150241912.png)

## Google Colab

#### What I do?

1. How to use.
2. How to import dataset from Google drive.
3. How to use the GPU.
4. How to run.

#### Problems

1. I have to interact with the platform, because the first time I leave the program running, I leave it for 3 hours and log off due to inactivity.
2. It is too slow ( 1 epoch - 1 hour 7 minutes.)

![](C:\Users\RA-IS\Pictures\Screenshots\Captura de pantalla (14).png)

![](C:\Users\RA-IS\Pictures\Screenshots\Captura de pantalla (15).png)

3. The first time that it disconnect me for inactivity, it reload all, my progress was lost.

4. I have to wait to use again the GPU.

![](C:\Users\RA-IS\Pictures\Screenshots\Captura de pantalla (16).png)

####  Possible solutions

1. Use pytorch.

2. Use Azure.

   ![image-20211013064744902](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013064744902.png)

   3. Buy subscription.

   ![image-20211013070409234](C:\Users\RA-IS\AppData\Roaming\Typora\typora-user-images\image-20211013070409234.png)