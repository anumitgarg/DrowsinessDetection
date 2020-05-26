# DrowsinessDetection
<b>Accident avoidance system that detects drowsiness of a driver based on facial cues and behavioral patterns.</b>

According to a WHO report on Road Traffic Injuries, approximately 1.35 million people die as a result of road traffic crashes. Road traffic injuries are not only results in fatal injuries but also causes economic losses to the individual, their families and a nation as a whole. These accidents cost most countries 3 % of their GDP. 

The study concluded that sleep related accidents are largely dependent on the time of day and account for a considerable proportion of vehicle accidents across the globe.

It has been found that facial expression has the highest correlation with the brain waves as a general index of drowsiness during monotonous driving. Thus, facial expressions can be considered a reliable measure of drowsiness. An algorithm that analyses facial expressions and predicts the level of drowsiness can act as the basis for an accident avoidance system. 


## Acknowledgement
This project has been developed under the guidance of Dr. R.K. Sunkaria, Head of Department, Electronics and Communication Engineering, National Institute of Technology Jalandhar.

We would also like to thank PyImage search tutorials for enhancing our understanding of Computer Vision technology for Drowsiness Detection. A special thank to Yash Kondawar's Github repo which helped us to dive much deeper in the same domain.

I also place on record, my sense of gratitude to one and all, who directly or indirectly, have lent their hands in this venture.

## Requirements
Following libraries are required for the project:
1. scipy
2. imutils
3. pygame
4. imutils
5. time
6. dlib
7. cv2

## Methodology
The design flow of the solution is as follows:
1.	Face detection using pre-trained Machine Learning Model.
2.	Landmark detection, identifying eyes, nose, mouth and jaw line.
3.	Calculation of aspect ratios (EAR and MAR). Once the features of a face are extracted we need to calculate the threshold values of eyes (sleepy) and mouth (yawn).
4.	Comparison of live aspect ratios with the threshold for the detection of drowsiness.
5.	Alarming the driver. Once the drowsiness is detected we need to alert the driver using a sound/ alarm.
