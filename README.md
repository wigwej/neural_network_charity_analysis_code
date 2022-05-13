# neural_network_charity_analysis_code

***Overview***

Our goal is to create a binary classifier that is capable of predicting whether applicants for a charity fun will be successfully funded by Alpha company. Over the last years, applicants for funding have exceeded 34000 orhanizations. We would deploy macjine learning and neural networks algorithms to preprocess, train, compile and evaluate the dataset to create a binary classifier.

***Results***

**Data Processing**
* IS_Successful is considered the target

* Catefories such as ASK_AMOUNT, ORGANIZATION, INCOME_AMT, SPECIAL CONSIDERATIONS, CLASSIFICATION APPLICATION_TYPE m  ake up the features

* USE_CASE, AFFILIATION should be dropped from input data


**Compiling, Training and Evaluation**

* I selected a varied number. At first I seleced 2 neurons and,
Hidden node=1 = 2neurons
Hidden node 2 =3 neirons
Activation = 'Relu'

* I achieved appoximately 73%

* To increase model performance, I
*   changed the number of neurons across both layers 
*   added hidden layersto increase 

***Summary***
The binary classifer was approximately 73% accurate but with a loss of about 50% ( too high). We need to increase the total number of parameters in particular trainable parameters for better results.
