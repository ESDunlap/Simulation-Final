Changes needed  
Complete routing logic for other seating sections (I plan on doing this tomorrow)
Creating total amount of money earned statistic  
Bug testing just to make sure everything still works  

#Changelog 0.7 - Eddie
Replaced all concession and merchandise stands with new version  
HalfTimeAcitivity Variable made to help with routing from seats to other areas  
General seating routing logic Setup  
  Will assign a trip number upon exiting as part of the trip variable setup  

# Changelog 0.6
- Erik  
Added in processing time and beer logic
Added in reneging logic for both kinds of queues
Added in proper time stamps

# Changelog 0.5 
- Erik  
Added in proper reneging logic for merchandise (changing for concessions should be easy)

# Changelog 0.4 - Eddie
-Added Section Assignment (TktType)  
-Added path logic (AssignedSeatNode) to assigned seats after security that can be used for anytime we need to send fans back to their seat  
-Different pictures for each type of entity based on Ticket Type  
-Set max population to 10,000  
-Added trip state variable for entities  

# Changelog 0.3
- Erik  
Created Merchandise and Food stalls  

# Changelog 0.2
- Erik  
Organized parts into final part  
Created Restrooms  
Added in Assigning Gender and Tickets  

# Changelog 0.1
- Erik  
Multiplied arrivals by 4 since the previous input was using arrival per hours but within a quarter hour per section  
Changed security and ticketing to both use input parameters  
Fixed bags being checked for everyone instead of everyone in 30  
Created bag chance element  
