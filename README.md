  # Transfer Learning Based Intrusion Detection in 5G and IoT Networks

 Development of a transfer learning system for the detection of cyber-attacks in 5G and IoT networks. Transfer learning will improve the accuracy and precision of cyber-attacks detection in 5G /IoT networks with limited computing capability and datasets with scarce labeled data.

 # How to run the code?

If you want to run the code to see the result of Transfer Leraning you must use the file ([code](https://github.com/polvalls9/Transfer-Learning-Based-Intrusion-Detection-in-5G-and-IoT-Networks/blob/main/codes/TL%20-%20CNN-TL.ipynb)). Download the zip file of the project and run the file marked in the link above.

The following is a summary of the content in the different code files:

- [BCNN-B.ipynb](https://github.com/polvalls9/Transfer-Learning-Based-Intrusion-Detection-in-5G-and-IoT-Networks/blob/main/codes/CNN-B.ipynb): Here the pre-trained model is generated with the BoT-IoT Dataset.
- [NONTL - CNN-TL.ipynb](https://github.com/polvalls9/Transfer-Learning-Based-Intrusion-Detection-in-5G-and-IoT-Networks/blob/main/codes/NONTL%20-%20CNN-TL.ipynb): In this code you can see the behaviour and results obtained, with graphs and figures, using a model without Transfer Learning.
- [TL - CNN-TL.ipynb](https://github.com/polvalls9/Transfer-Learning-Based-Intrusion-Detection-in-5G-and-IoT-Networks/blob/main/codes/TL%20-%20CNN-TL.ipynb): In this code you can see the behaviour and results obtained, with graphs and figures, using a model with Transfer Learning (CNN-TL).
- [Transfer Learning.ipynb](https://github.com/polvalls9/Transfer-Learning-Based-Intrusion-Detection-in-5G-and-IoT-Networks/blob/main/codes/Transfer%20Learning.ipynb): In this code you can see the behaviour and results obtained, with graphs and figures, comparing the model with and without Transfer Learning in the UNSW-NB15-Test dataset. 
- [UNSW-NB15_Generate_Basic_Train_Test_Test+.ipynb](https://github.com/polvalls9/Transfer-Learning-Based-Intrusion-Detection-in-5G-and-IoT-Networks/blob/main/codes/UNSW-NB15_Generate_Basic_Train_Test_Test%2B.ipynb): In this code the different subdatasets of UNSW-NB15 are generated.


# 1. **Introduction**
   ## 1.1 **Statement of purpose**
The purpose of this project consists of the development of a Transfer Learning (TL) based system for the detection of cyber-attacks in 5G and IoT networks. Traditional Deep Learning based intrusion detection systems are capable of detecting and classifying known cyber-attacks, but they fail in the detection of unknown (zero-day) attacks. 

Transfer learning will improve the accuracy and precision of unknown cyber-attacks detection and classification in 5G/IoT networks, with limited computing capability and datasets with scarce labelled data. First, existing datasets for IoT networks will be studied to choose the best option for the source and target domains. Then, DL and transfer learning methods will be analysed to select the most adequate for the system. Finally, the system will be developed and tested.
## 1.2 **Project requirements**
- Detection of unknown attacks in 5G/IoT networks, considering that edge devices in these networks have limited computing capability.
- Detection of attacks considering scarce datasets in 5G/IoT networks. 
- The proposed model based on transfer learning should obtain better accuracy in the detection and classification of unknown attacks than the achieved by DL based solutions.
## 1.3 **Project specifications**
- Be able to detect unknown attacks in a 5G /IoT network. 
- Achieve high attack detection accuracy, whether there are new attacks or attacks already seen by the system. 
- Achieve high attack detection classification, whether there are new attacks or attacks already seen by the system. 
- Achieve high accuracies in scarce datasets. 
- Detect well-know IoT networks attacks: Distributed Denial of Service (DDoS), DoS, Keylogging, Data Theft, etc. attacks.
- Be able to operate in systems with limited computing capacity.

