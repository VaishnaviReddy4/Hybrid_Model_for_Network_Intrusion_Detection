### A Prophetic Hybrid Model to predict Intrusions using Network Data Traffic Analysis.

>* #### **Abstract**
An innovation for improvising protection against complicated threats. The whole idea includes two main challenges of Network Intrusion Detection. 
The problem statement initially is to monitor network availability and activity to identify anomalies (Network Traffic Analysis) and to detect the unknown malware attacks over the network (Intrusion Detection). 
Taking machine learning results into consideration, a further step includes a statistical analysis to analyze the trends and strongly correlated features. A systematic description scheme for regulating the descriptions approach of IDSs based upon their descriptions, without necessitating experimentation. 
Using various supervised machine learning techniques and deep learning techniques to train and build multiple classification models that can classify attack type of network traffic versus normal type of network traffic (Also determines various cyber attacks) . 
We compare the test accuracies of these multiple classification models to identify the best model for performing network intrusion detection. 


>* #### **Scope**
A well-known literature that has surveyed traditional learning-based techniques for NTA and NIDS and highlight their differences with our work.
To use supervised models for NTA and NIDS, the key characteristics and their applications are discussed.
Review on the advanced DL techniques used in the main applications and their applicability in the NIDS domain.
A survey on the literature that uses DL techniques in fields of: Network Traffic including traffic classification, Traffic monitoring and network security; Intrusion Detection including classification, feature analysis and extraction. 
A hybrid combination model of supervised machine learning algorithms that detects few attacks and identify intrusions.
A hybrid combination model of Deep Learning techniques like Auto Encoder, Artificial Neural Networks, Perceptron's and etc.
Performances are analysed and the best results are taken out and can be implemented in real-time.
The challenges and future research directions regarding NTA and NIDS are the key motives that are to be achieved.


>* #### **NSL KDD Dataset and its Description**
KDD Cup '99 is one of the most popular and widely used dataset for IDS. It contains approximately five and two million records for training and testing respectively. Each record contains 41 different features or attributes and is labeled as either normal or attack. The attacks are classified into four different types as Denial of Service (DoS), Probe, Remote to Local (R2L), and User to Root (U2R).
NSL-KDD is the revised and refined version of the KDD Cup '99 dataset by removing several of its integral issues. This dataset is also a 41 feature dataset with the attacks divided into four classes as mentioned in KDD Cup '99.
For this model, we use the NSL KDD database which has the latest and updated feature set and is suggested to solve some of the inherent problems of the KDD'99 data set.
It does not include redundant records in the train set, so the classifiers will not be biased towards more frequent records.
There are no duplicate records in the proposed test sets; therefore, the performance of the learners are not biased by the methods which have better detection rates on the frequent records.


>* #### **Hybrid Methodology**
The idea of hybrid methodologies that includes combination of models. Hybrid models with a combinational set of supervised classifiers are used to get a result of the best type.The attack types of the NSL-KDD dataset are clustered into four different attack classes:
* **DoS (Denial of Service):** DoS include attacks that cause the slowing or shutting down of a machine by sending more traffic information to the server than the system is able to handle. DoS attacks affect legitimate network traffic or access to services.
* **R2L (Root to Local):** R2L include attacks which provide illegal local access to a machine by sending remote deceiving packets to the system.
* **U2R (User to Root):** U2R includes attacks which provide root access. In this case, the hacker finds out the system vulnerability and starts using the system as a normal user.
* **Probe (Probing):** Probe includes attacks able to avoid the security control systems by gathering information about the network.


