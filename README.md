CyberScape
---------------
Idea submission for Nasa space apps challenge - A Flood of Ideas
---------------
Our Problem Statement is to Estimate the amount of infrastructural damage that may be caused by floods.
After floundering around, wildly grasping at straws for ideas and application of machine learning concepts, we settled on using the HIFLD tsunami events data linked in the resources tab, to narrow our estimation to tsunamis.
We decided that we will be approaching this as a basic multiple classification problem in machine learning, where:
 
 -> Given certain inputs like Cause code (0- Unknown, 1- Earthquake, so on), Location (Longitude & Latitude), Tsunami Intensity, and Distance from source, the system will learn
     to predict the tsunami's Damage Amount Code
  
	-> The Damage_Amount measure is a number from 1-4, where
	  1 = Damage to infrastructure amounts to <= $1 million 
                                                           
	  2 = Damage to infrastructure amounts to some amount from $1-5 million 
                                                           
	  3 = Damage to infrastructure amounts to some amount from $5-24 million
                                                           
  	4 = Damage to infrastructure amounts to >= $24 million 

The training dataset we used contains 27,000+ records of tsunami events, stored in a csv file. We used a sequential model, and we are comparing the effectiveness of different algorithms to choose the most suitable one.
