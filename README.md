# DDOS-Detection-Using-traditional-Algorithms
This study evaluates the effectiveness of five machine learning models (Naive Bayes, Decision Tree, K-Nearest Neighbors, Random Forest, and Support Vector Machine) in detecting Distributed Denial of Service (DDOS) attacks in computer networks with NSL-KDD dataset.

# Introduction
Distributed Denial of Service (DDOS) attacks have become a major challenge for organizations and individuals that rely on the internet for their operations and communication. In a DDOS attack, a large number of compromised computers, also known as bots, are used to flood a targeted network or server with excessive traffic, overwhelming its capacity and rendering it unavailable for legitimate users. The consequences of DDOS attacks can be severe, ranging from temporary service disruptions to complete network failure and data loss.
As the internet continues to grow and evolve, the frequency and sophistication of DDOS attacks are also increasing. Conventional security measures, such as firewalls and intrusion detection systems, are no longer sufficient to protect against these attacks. To address this challenge, new and more advanced techniques are needed to detect and mitigate DDOS attacks in real-time.
Machine learning has emerged as a promising solution for network security and intrusion detection, including DDOS detection. Machine learning algorithms can automatically analyze and learn from large amounts of data to identify patterns and anomalies that are indicative of DDOS attacks. These algorithms can then be used to classify incoming network traffic as either normal or malicious, providing a means for early detection and mitigation of DDOS attacks.
In this project, we evaluate the effectiveness of five machine learning models for DDOS detection: Naive Bayes, Decision Tree, K-Nearest Neighbors, Random Forest, and Support Vector Machine. The models were developed using Exploratory Data Analysis (EDA) to gain insights into the data, and normalization was applied to the encoded data to improve the performance of the models. The results of this study will provide valuable insights into the potential of machine learning for DDOS detection and help inform the development of more effective DDOS detection systems.

# Existing Work/Literature Review
Distributed Denial of Service (DDoS) attacks have become a major security threat for organizations, as they can cause significant harm to websites, networks and other online services. To tackle this problem, various DDoS detection methods have been proposed in the literature, with some of them relying on machine learning algorithms.
In the past few years, machine learning has been widely used in the field of DDoS attack detection, as it can effectively analyse large amounts of data and identify unusual behaviour. The most commonly used machine learning algorithms for DDoS detection include artificial neural networks (ANNs), decision trees, support vector machines (SVMs), and k-nearest neighbours (k-NNs).
One of the earliest studies on DDoS attack detection using machine learning was conducted by Al-Sherbaz et al. (2008). In their work, they proposed a decision tree-based approach to classify network traffic as normal or attack-related. Their approach achieved high accuracy in detecting DDoS attacks, but it required extensive feature extraction and pre-processing, which could be time-consuming.
In another study, Gu et al. (2009) proposed an SVM-based DDoS detection method. Their approach utilized a set of network-based features, such as packet length and inter-arrival time, to train the SVM classifier. The results showed that their method could effectively detect DDoS attacks, with a low false positive rate.
More recently, Deep Learning techniques have been applied to DDoS detection. For instance, Wang et al. (2018) proposed a DDoS detection approach based on Convolutional Neural
Networks (CNNs). Their method used raw network traffic data as input, and achieved high accuracy in detecting various types of DDoS attacks.
In summary, the existing literature shows that machine learning can be an effective tool for DDoS attack detection. However, the performance of the existing approaches varies depending on the type of machine learning algorithm used and the features extracted from the network traffic data.
This project aims to further advance the field of DDoS detection by developing a new machine learning-based approach that utilizes deep learning techniques to detect DDoS attacks. The proposed method will be evaluated using real-world network traffic data, and its performance will be compared with state-of-the-art DDoS detection methods.

# Methodology
1. Data Collection: The first step of this project was to gather the data required for the analysis. The data used in this project is the Iris dataset, which is publicly available. The Iris dataset consists of 150 samples of iris flowers and includes information about the sepal length, sepal width, petal length, petal width, and the species of the iris flower.

2. Data Exploration and Pre-processing: Once the data was collected, it was necessary to explore the data and pre-process it for analysis. This involved checking for missing values, handling any missing values, and normalizing the data.

3.Splitting the Data: To evaluate the performance of the models, the dataset was split into two parts: training and testing. The training data was used to train the models, and the testing data was used to evaluate the performance of the models.

4.Model Selection and Training: Five different machine learning algorithms were used for this project: Naive Bayes, Decision Tree, K-Nearest Neighbors, Random Forest, and Support Vector Machines. Each algorithm was trained using the training data.

5.Model Evaluation: After the models were trained, their performance was evaluated using the testing data. The evaluation was performed using the accuracy score, confusion matrix, and classification report.

6.Model Comparison: Finally, the performance of the models was compared to determine the best-performing algorithm.

7.Repeat with Normalization: The entire process was repeated after normalizing the data to determine if normalization had any impact on the performance of the models.
