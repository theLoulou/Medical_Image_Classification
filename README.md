# Medical_Image_Classification
Classification of skin lesion images from the HAM10000 data set using Resnet models and image generation.  

This work was done as a project for the class SYS800 of the ETS. It is not a peer reviewed article and the opinions/results are my work alone. Check the sources in the report and try the code yourself for more information.

The purpose of this project was to become more familiar with Keras Image processing functions as well as to learn about medical image classification and image generation. I used the Resnet152 model (He & al, 2015) to classify the skin lesion images of the data set HAM10000 (Tschandl & al, 2018). This data set contains more than 10 000 images of skin lesions. The different classes in the data set are heavily unbalanced.

I used 3 different methods to deal with the unbalanced classes:
  - 'classical' image generation which consists in rotating/shifting the original images of the under represented classes to generate new ones;
  - ADASYN, originally a data generation technique for vectorial data, to generate new samples that are representative of their class while being more diverse than the orginal image;
  - weighting the classes, to give more importance to the under represented classes during training;
  
 In this repo, you can find the notebooks containing the codes for the 3 different methods, as well as the final report for this project. Once again, it may contain some innacuraccies or mistakes as it is a student project, so test and check everything yourself to be sure !  
  
