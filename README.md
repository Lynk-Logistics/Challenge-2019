# Lynk Logistics Challenge-2019
Please Fork the challenge and submit pull requests.

## Trip Distance Problem:

When a lynk trip is finished, we have to calculate the total distance of the trip and time taken for the trip. Time is straightforward, endtime - starttime. But calculating the trip distance is not so easy. There may be inaccurate lat longs since GPS is not as accurate in all places, some times the difference is absurd. 
Given a list of lat longs and the time taken to reach from start to end of trip. Calculate the total distance of the trip, ignoring all the wrong lat longs. 

	 	 	
## Diner problem

There are 4 chefs available in the diner.
Following are the list of Chefs and their efficiency. If normal time taken to make a pasta is 10 minutes, A will make it in 8 minutes 20 seconds, B will make it in 12 minutes 30 seconds, C will make it in 6 minutes 40 seconds, D will make it in 10 minutes.

Chef		Efficiency  
A		    1.2x  
B		    0.8x  
C		    1.5x  
D		    1x  

Create a diner system which accepts orders placed by customer and and assign them to the chefs. One chef can prepare only one dish at a time. The system should assign to chefs efficiently in such a way that the waiting time of customers are the least possible value. Each customer can order one or more dishes.

Normal time taken to prepare each dish:  
Pasta – 10 min  
Noodles – 5 min  
Burger – 8 min  
Fries – 4 min  
Nuggets – 7 min 30 sec  
Fried Rice – 13 min 20 sec  

The solution should be a web application (Can have UI but not must) with Rest APIs.


