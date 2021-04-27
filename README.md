# Project Name: Hate speech/offensive language detection with Bengali Dataset
---
## _Supervised By: Prof. Animesh Mukherjee, CSE, IIT KGP_
## _Mentored By: Mithun Das, Research Scholar, CSE, IIT KGP_

------
### Hate Speech:  
Public speech that expresses hate or encourages violence towards a person or group based on something such as race, religion, sex, or sexual orientation.
# Task-1: 
>To classify the dataset texts into Hate & Non-Hate Class
_____
### Dataset: 
#### Link:
 [bengali-hate-speech-dataset](https://www.kaggle.com/naurosromim/bengali-hate-speech-dataset)
#### Details: 

 - The dataset consists of comments taken from Facebook and Youtube.                      
 - Category: Sports, Entertainment, Crime, Religion, Politics, Celebrity, Meme and others.

    |Hate Comments| Non-Hate Comments|
    | ------ | ------ |
    | 10K | 20K |


## Analysis Done:

- N-Gram Analysis
- Generating Word2Vec and FastText Embddings
- Using LR, SVM, LSTM, Bi-LSTM to classify those embeddings



## Results:
### Non-Hate Class:
#### Top-20 Unigrams 

|Word| Count|                       
|-------|------  |                  
|(না,)  |   4199|                              
|(করে,)  |        2915 |
|(এই,)    |       2869 |
|(আর,)    |     2696  |
|(কি,)    |        2597|
|(কে,)    |        1876|
|(আমি,)   |     1616|
|(আমার,)   |   1603|
|(আপনার,)   |1514|
|(কথা,)      |   1504 |
|(ভাই,)      |    1423|
|(ও,)        |     1378|
|(জন্য,)     |     1347|
|(যে,)       |      1344|
|(একটা,)     |   1327|
|(ভালো,)     |   1280|
|(আপনি,)     |  1278  |
|(অনেক,)      |  1232 |
|(তার,)        |   1219 |
|(থেকে,)        |  1166 |

#### Top-20 Bigrams 
|Word| Count|                       
|-------|------  |  
|(মনে, হয়)  |             233
|(হা, হা)    |              167
|(অনেক, ভালো)  |    126
|(করার, জন্য)   |       125
|(খুব, ভালো)     |      119
|(জাফর, ইকবাল)   |  117
|(কথা, বলে)      |      115
|(হবে, না)       |         113
|(না, করে)       |        112
|(এই, সব)        |       112
|(আমার, মনে)    |104
|(ভালো, লাগে)    |     100
|(না, কেন)        |       94
|(হয়, না)          |       93
|(এই, রকম)         |    91
|(হতে, পারে)    |        85
|(না, হলে)       |        84
|(করা, হোক)       |     82
|(কি, করে)        |       82
|(মিজানুর, রহমান)  |  80

#### Top-20 Trigrams 
|Word| Count|                       
|-------|------  |  
 |(হা, হা, হা)                |            76
|(আমার, মনে, হয়)             |    61
|(না, না, না)               |           52
|(আমি, মনে, করি)               |   49
|(করে, বমি, করে)              |      29
|(জাফর, ইকবাল, স্যার)        |   28
|(অনেক, অনেক, ধন্যবাদ)      | 27
|(বি, এন, পি)                |        25
|(সাকিব, আল, হাসান)         |  24
|(খুব, ভালো, লাগলো)        |    24
|(মিজানুর, রহমান, আজহারী) | 22
|(থেকে, বের, করে)            	|     20
|(হড়হড়, করে, বমি)              |  20
|(অনেক, দিন, পর)              |  18
|(ছি, ছি, ছি)                |         18
|(তা, না, হলে)              |        18
|(হড়, হড়, করে)             |        17
|(যদি, পারেন, তাহলে)      |      17
|(অনেক, ভালো, লাগলো)     |  17
|(ছিঃ, ছিঃ, ছিঃ)|                     16

### Hate Class:
#### Top-20 Unigrams 

|Word| Count|                       
|-------|------  |    
|(এই,)          | 1815
|(না,)          |  1549
|(কি,)      |      1205
|(আর,)       |  1148
|(করে,)      |    1104
|(তুই,)      |     1000
|(কে,)       |     912
|(বাচ্চা,)   |      903
|(একটা,)     |   885
|(তোর,)      |   857
|(মাগি,)     |    635
|(সব,)       |    626
|(কুত্তার,)  |      607
|(খানকির,)   |  581
|(তো,)       |    568
|(মাগির,)    |   539
|(শালা,)     |   528
|(কথা,)      |   513
|(যে,)       |     483
|(জুতা,)    |    481

#### Top-20 Bigrams 

|Word| Count|                       
|-------|------  |   
|(কুত্তার, বাচ্চা)  |         257
|(খানকির, পোলা)     |  203
|(মাগির, মাগির)     |    127
|(মনে, হয়)           |     124
|(মাদার, চোদ)       |    102
|(তুই, একটা)        |     79
|(খানকি, মাগি)     |     77
|(এই, সব)         |        76
|(জুতা, দিয়ে)    |         60
|(এই, কুত্তার)  |           59
|(কথা, বলে)         |     58
|(এই, খানকির)      |    58
|(মারে, চুদি)      |        57
|(লুচ্চা, লুচ্চা) |          56
|(হা, হা)          |         54
|(জুতা, মার)      |       53
|(জুতা, পিটা)    |        53
|(ফাসি, চাই)    |         49
|(মাদার, চুদ)   |          49
|(কে, জুতা)     |          49

#### Top-20 Trigrams 

|Word| Count|                       
|-------|------  |  
 |(মাগির, মাগির, মাগির)  |        126
|(লুচ্চা, লুচ্চা, লুচ্চা)|               52
|(হা, হা, হা)            |               24
|(চোর, চোর, চোর)         |         20
|(জুতা, পিটা, করা)       |          19
|(জুতা, পেটা, করা)       |          18
|(জুতা, মারা, দরকার)     |         18
|(ছি, ছি, ছি)            |              17
|(থেকে, বের, করে)        |          16
|(এই, খানকির, পোলা)      |      16
|(এই, কুত্তার, বাচ্চা)   |             15
|(কুত্তার, বাচ্চা, তুই)  |              15
|(আমার, মনে, হয়)         |        15
|(তোর, মারে, চুদি)       |           13
|(ছিঃ, ছিঃ, ছিঃ)         |            13
|(করতে, পারে, না)        |          13
|(পাপন, খানকির, পোলা)     |   13
|(মাগি, মাগি, মাগি)        |        12
|(কুত্তার, বাচ্চা, কে)      |           12
|(খানকির, পোলা, তোর)         | 12

### Model Results:
|Models| Accuracy|                       
|-------|------  |  
| Word2vec + SVM|76.85
|Word2Vec + LSTM|67.35
|Word2Vec + Bi-LSTM|67.02
|FastText + SVM|80.88
|FastText + LSTM|67.21
|FastText + Bi-LSTM|66.50
|BengFastText + SVM|81.18
|BengFastText + LSTM|66.20
|BengFastText + Bi-LSTM|67.43

# Task-2: 
> Classifying  bengali texts them into political, personal, geopolitical, and religious hates
_______
## Dataset:
#### Link:
[Bengali-Hate-Speech-Dataset](https://github.com/rezacsedu/Bengali-Hate-Speech-Dataset)
#### Details: 
 - The dataset consists of personal, political, geopolitical and religious hates.
 
    |Category|Count|
    |-------|---------|
    |Personal     |    1850
    |Geopolitical|        1408
    |Religious |           778
    |Political|                662

### Analysis Done:
 - Using LR, NB, SVM, KNN, RF, GBT  classifier to classify texts into different categories 
### Results:

| Classifier |Precision |Recall |F1 |MCC|
|------|-----|----|-----|----|
|LR|0.65|0.65|0.68|0.510
|NB|0.64|0.64|0.64|0.494
|SVM|0.65|0.64|0.63|0.499
|KNN|0.64|0.55|0.50|0.395
|RF|0.68|0.68|0.67|0.547
|GBT|0.69|0.67|0.66|0.549



