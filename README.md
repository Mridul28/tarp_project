# Optimal Route Detection for Combating Road Accidents
Abstract
------------------
Android phones are widely used due to its features like GPS, Computational ability, internet
connectivity. There are many web applications which help to user in order to provide solutions
to many problems related to their day to day life. Road accidents are the major problems in urban
areas. Also due to the delay in reaching of the ambulance to the accident place increases the
chances of the death of victim. So, in order to provide solution for this problem, we built a web
application that allows a passer by or victim to report an accident which creates a list of accidents
in a place which in turn can be accessed by the nearby hospitals allowing the nearest hospital to
take an action and provide the victim with the required medical treatment. We define one user
defined algorithm for reporting and listing accidents. While adding the accident the user enters
his/her location details which then are pinned in the google maps. At the time of registration,
application takes personal information like blood group, name, email etc. If an accident trigger
occurred, then this information will be accessed by the emergency service centers.

Keywords: Google maps, Internet, Location


Intoduction
------------------
Every year, road traffic injuries cause more than 1.2 million deaths and have a profound effect on
health and development. It is the leading cause of death among young people between 15 and
29 years of age, and it costs governments about 3% of GDP. The global challenge of climate
change has been inadequately addressed despite its massive - and largely preventable - human
and economic toll.
Around 5 lakh road accidents occurred in India during the year 2010, resulting in the deaths of
134,513 people and the ill-treatment of more than 5 lakh persons. These numbers convert into 1
road accident each minute and 1 road accident death every four minutes. According to the
Reserve Bank of India, the absence of the Indian saving due to road accidents and fatalities likely
at 3% of GDP in 1999-2000 is mainly due to the fact that 53.1% of road accident victims were in
the age group of 25 to 65 years old in 2010, with pedestrians, bicyclists, and two-wheelers,
including the most unguarded road users, accounting for about 40% of all fatalities.


Literature Survey
------------------
Accident Detection System Web Application [1]: 

The paper aims to implement a Cooperative Sensing for Improved Traffic Efficiency. It develops an
AI for the single player game using minimax and alpha- beta pruning algorithms. It has a very
simplistic implementation of the Traffic sensing with not a lot of focus given on the AI.


Accident Detection using Convolutional Neural Networks [2]

The main goal is to integrate a system capable of detecting an accident from a video sequence fed
to it by a camera. The goal is to detect a crash within seconds of it happening by using advanced
deep learning algorithms that use complex neural networks (CNN or ConvNet) to analyze captured
images from camera-generated video. They have focused on deploying this system on highways
where traffic is less dense and timely help to those involved in an accident is rare. In this system,
they have a Raspberry Pi 3 B+ Model which acts as a portable and remote computer to be set up
on a CCTV camera. This model was then implemented on a Raspberry Pi using TensorFlow, OpenCV
and Keras.

Traffic Density Measurement using Image Processing: An SVM approach [3]

Their system consists of 4 components-
• Traffic management system
• Road way system
• MATLAB
• SVM classifier algorithm V.
So their proposed system needs the traffic management system, the roadway system. The CCTVs
in the road will take the images of the current state of the traffic in roads. The images will be sent
to be processed through server. Then the images will go through their proposed systems to detect
the traffic density. The SVM classifier will be used to classify data. The process has three phases.
First one is the image analysis part, second is the object detecting and counting part and the final
part is the result representation using SVM classification algorithm.

Accident Detection and Enhancement of Health Services[4]

This paper focuses on building an android application which detects accident automatically as well
as sends notification to nearby emergency services like hospital, ambulance, police station along
with his personal information. It uses an user defined algorithm for accident detection which uses
GPS location and Speed of car for recognizing the accident.

Mobile Web application for Automatic Accident Detection and Multimodal Alert[5]

The proposed accident detection algorithm receives inputs from the vehicle, via ODB-II, and from
the smartphone sensors, namely the accelerometer, the magnetometer and the gyroscope. The
Android smartphone is also used as human machine interface, so that the driver can configure the
application, receive road hazard warnings issued by other vehicles in the vicinity and cancel
countdown procedures upon false accident detection.


Project Workflow
------------------
![image](https://user-images.githubusercontent.com/72341082/217732531-b8860f84-adba-482d-948b-90bc5a15608a.png)
