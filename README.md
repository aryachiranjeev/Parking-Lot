# Parking-Lot

# Team Name- REAL-LIFE HACKERS

# PROBLEM STATEMENT- 

Smart Parking for Smart Cities of the future!!
Where shuould I park my car ??
As we know car parking is major problem issue now-a- days and frustrating for people to find the parking spaces in malls and other parking areas .

# SOLUTION TO PROBLEM-

1) So to solve this probelm , there will be an App which will help the user to detect the parking spot in the parking lot if available which will make easy  for the user to find the parking space from the app in which the parking area avaibility will be updated after every 10 seconds (will show  where there is parking space available by using automated cameras in parking places).

2) Extra feature of this App will be that user can also book  there favourable parking slot in advance thorugh this app by selecting the date and timings for how many hours  they want to park there car and on which date in advance , in just Rs.20 extra as advance booking charges and Rs.10 per extra half an hour if vehicle parked after ending of alloted time.

3) Also , this app will show the directions to the user when user enters the parking lot  to the parking spot alloted to the user thus helping the user to easily reach to its parking slot.

4) Due to automated cameras in parking lot at every 10 seconds the parking lot condition get updated  by telling which parking spots are empty or occupied.(Green box for empty parking spot)

# APPROACH-

1) We created the segmented dataset for parking spot images of parking area in different weather conditions.

2) We train the convolutional neural network model for the segmemented dataset which contain various empty  and occupied  parking slots in different weather conditions and got training  Accuracy  97%  and Validation Accuracy 98% .
 
3) Then we annotated  the full parking lot using OpenCv  by detecting the parking slots in the parking area and finding there co-ordinates and saved them as pickel file.

4) After combining  these two in the whole parking area we detected which parking slot is empty and which is occupied.(Green Box  for Empty).

5) We saved  the  model and put it into the andoid app through  which user can easily access the parking slot in the parking area  and can do advance booking at just Rs.20 extra advance booking charges .

6) We used  firebase to create  datsbase  to  store the information of every user like name , email , the parking slot user booked ,payment done by user and many other details.

# LINK TO ARCHITECTURE-
# SOLUTON ARCHITECTURE-https://github.com/aryachiranjeev/Parking-Lot/blob/master/project%20architecture.docx
# TECHINCAL ARCHIECTURE- https://github.com/aryachiranjeev/Parking-Lot/blob/master/Read%20Me(Technial%20Architecture).docx

# PRESENTATION LINK- 
