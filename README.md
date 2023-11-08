# EX 9: Simulating Classification using WEKA Data mining and Analysis Tool

## Date: 06/10/2023

## AIM:
To perform a classification technique using WEKA tool
## WEKA:
<div align="justify">
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements.
WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram −

![image](https://github.com/vijayarajv1704/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121303741/98d0e21f-af04-4514-b511-583045468c68)
   
## CLASSIFICATION:
<div align="justify">
Classification in data mining is a common technique that separates data points into different classes. It allows you to organize data sets of all sorts, including complex and large datasets as well as small and simple ones. It primarily involves using algorithms that you can easily modify to improve the data quality. This is a big reason why supervised learning is particularly common with classification in techniques in data mining. The Classification algorithm is a Supervised Learning technique that is used to identify the category of new observations on the basis of training data. In Classification, a program learns from the given dataset or observations and then classifies new observation into a number of classes or groups. Such as, Yes or No, 0 or 1, Spam or Not Spam, cat or dog, etc. Classes can be called as targets/labels or categories.<br>
  
## PROCEDURE
1. Load the data file into the WEKA explorer. The data can be loaded from the following sources −
   Local file system
   Web
   Database
2. Click on the "Open file" button. A directory navigator window opens as shown in the following screen − <br>
  ![image](https://github.com/vijayarajv1704/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121303741/0b245d6b-6be7-4031-9ef8-f6feb9cfcf3c)

3. Click on the Classify tab, and you would see the following screen <br>
  ![image](https://github.com/vijayarajv1704/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121303741/ef55d57b-1d5b-4fcd-8ea4-6243089e68a9)

4. Now, keep the default play option for the output class −<br>
   ![image](https://github.com/vijayarajv1704/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121303741/cd7a1546-feee-407f-a5fa-f5a72b70e8d0)

5. Click on the Choose button and select the following classifier − weka→classifiers>trees>J48. <br>
  ![image](https://github.com/vijayarajv1704/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121303741/e9977cf1-c6fc-487e-b495-943f019f7bd9)

6. Click on the Start button to start the classification process. After a while, the classification results would be presented on your screen as shown here −<br>
  ![image](https://github.com/vijayarajv1704/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121303741/3cb621c1-3ed2-4911-98b4-e0448ec413ae)

7. To see the visual representation of the results, right click on the result in the Result list box. Several options would pop up on the screen as shown here −<br>
  ![image](https://github.com/vijayarajv1704/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121303741/db7bf412-0bb9-4d8a-bf89-cc1baceeea5b)

8. Select Visualize tree to get a visual representation of the traversal tree as seen in the screenshot below −<br>
   ![image](https://github.com/vijayarajv1704/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121303741/3fa36104-893b-4ada-8475-075f96ff9de7)

9. Selecting Visualize classifier errors would plot the results of classification as shown here −<br>
   ![image](https://github.com/vijayarajv1704/EX-9-Simulating-Classification-using-WEKA-Tool/assets/121303741/ca7ea648-3ea6-4791-91a0-2081503ed986)

10. A cross represents a correctly classified instance while squares represents incorrectly classified instances. At the lower left corner of the plot you see a cross that indicates if outlook is sunny then play the game. So this is a correctly classified instance.<br>

## RESULT:
Thus the simulation of classification technique has been executed using WEKA tool successfully.
