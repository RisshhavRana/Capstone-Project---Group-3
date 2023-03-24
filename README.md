# Capstone-Project---Group-3
Drowsiness Detection in Truck Drivers

Assessment – Project proposal

1.	Problem Statement
One of the major contributing reasons to traffic accidents is truck driver weariness. Some long-distance drivers report falling asleep behind the wheel. Such sleep loss and daytime weariness can have major negative effects on one's personal and professional life. Drowsiness detection is a crucial aspect in several domains such as transportation, healthcare, and work safety, as drowsiness can lead to serious accidents or mistakes. The current methods for detecting drowsiness are either intrusive or unreliable. Truck drivers may become fatigued while operating a vehicle for a variety of reasons, including stress and lack of sleep. 
Our endeavour intends to create a drowsiness detection agent using Machine Learning to stop and lessen such tragedies.

2.	Why is this problem important?
Drowsy driving is a serious safety hazard, as it impairs a driver's ability to react to changing road conditions and increases the risk of accidents. In fact, drowsy driving is estimated to cause over 100,000 crashes and 1,550 deaths in the United States each year.
Drowsy driving can lead to fatigue-related accidents, which are often more severe than other types of accidents. This is because drowsy drivers are more likely to lose control of their vehicle, fall asleep at the wheel, or have delayed reaction times.
By detecting drowsiness in real-time and alerting the driver, the system can help to improve road safety and reduce the number of fatigue-related accidents.
The system can also increase awareness among drivers about the dangers of drowsy driving and encourage them to take breaks or rest when needed.
Legal Compliance: In some regions, it is mandatory to install drowsiness detection systems in commercial vehicles, and failure to comply with these regulations can result in fines or penalties.


3.	Solution Outline
a.	The first step would be to collect a diverse and representative dataset of drowsy and non-drowsy individuals.
b.	We will process the collected data to remove noise, outliers, and irrelevant information. The data should also be normalized to ensure that it is suitable for use in Machine Learning models.
b.	We will deploy simulation on our laptop by accessing our camera using python and get image frames. We will be using OpenCV and Keras using which we can achieve our objectives. We will gather images from a camera using OpenCV and feed them into a Deep Learning model.
d.	In addition we will be adding some more feature like yawning to improve the reliability on the system.


4.	Tools/Technology Required 
a. Physical sensor if required like Camera.
b. Python.
c. Machine learning.
d. Image Processing library like OpenCV.
e. ML libraries like Tensor Flow, Keras.
f. Visualization and reporting tools, such as Matplotlib, Seaborn, and Plotly.


5.	How does this solution compare to existing solutions, or to previous attempts to solve this problem?
In recent years, there has been a great deal of research into the use of automatic driver drowsiness detection to minimise traffic accidents and fatalities. These systems consist of image processing techniques using deep learning which makes a prediction if the driver behind the wheel is sleepy. Many studies have been conducted to produce drowsiness systems. There are initiatives where people have tried to create a system that can tell if a driver is nodding off by looking tired. Also, there are systems base on the steering wheel movement to detect the drowsiness, but such systems are heavy depended on conditions of road which creates a bias when they are applied to a vehicle driven on bad condition roads. To create an effective model, we will be evaluating many other features, such as yawning and nodding the head behind the wheels, which will contribute to the development of a more dependable system.

6.	How are you evaluating your solution? And how feasible is it?

A machine learning-based sleepiness detection system must have its performance evaluated in several different ways.
a.	By calculating the Accuracy, which gives us the measure of true positive and true negative.

b.	Secondly by calculating the Sensitivity or Recall rate. This metric will tell us how many total drowsiness samples were correctly identified as drowsiness.
    (True Positives) / (True Positives + False Negatives)

c.	Then by calculating Specificity. This metric will tell us how many total non-drowsiness samples were correctly identified as non-drowsy.
    (True Negatives) / (True Negatives + False Positives)

d.	Then we will calculate the Precision. This metric will give us the proportion of samples identified as drowsy that are drowsy.
    (True Positives) / (True Positives + False Positives)


7.	Ethical Concerns 

a.  Systems for detecting drowsiness gather sensitive information, including physiological signs and facial expressions, which could be used to learn about a person's health, way of life, or habits. This information runs the danger of being abused or revealed without permission, which would be bad for the person's privacy.
b. Machine learning models that have been trained on data are used by drowsiness detection systems, but there is a chance that these models won't be accurate or that they'll yield biased results.
c. Systems for detecting drowsiness are intended to make decisions based on data, and there is a chance that these conclusions may be harmful or wrong. Additionally, there is a chance that the system will break down, which could cause hurt or damage.


8.	Impact on stakeholders

There are several stakeholders for drowsiness detection system. But as we are making this system dedicatedly for truck drivers they will be our primary stakeholders.
a.	Truck drivers: The system can help providing road safety by reducing the risk of accidents for truck drivers.
b.	Trucking companies:  As our system is providing with road safety which will decrease the chances of road accidents, trucking companies can increase their      
    profitability.
c.	Government Agency:  Our system will provide improved public road safety, and reduction in cost which are associated with road accidents.
d.	Insurance companies: They would benefit from fewer claims and greater safety, which would result in lower costs and greater profitability.
e.	Pedestrian: Preventing accidents will reduce the risk of damage to pedestrians.


9.	References

a.	S. Lal and A. Craig, “A critical review of the psychophysiology of driver fatigue,” Biol. Psychol., vol. 55, no. 3, pp. 173–194, 2001.
b.	E. Hitchcock and G. Matthews, “Multidimensional assessment of fatigue: A review and recommendations,” in Proc. Int. Conf. Fatigue Manage. Transp. Oper., Seattle,       WA, USA, Sep. 2005.

 
Group Members 

a.	Abhijeet Chaudhari 
b.	Harshilkumar Patel 
c.	Kishankumar Patel 
d.	Rishav Rana 


