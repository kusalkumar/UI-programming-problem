# UI-programming-problem
Creating the table where user can select the no.of rooms and persons for booking 
output of the program look like table having three columns look like below
 
     Choose number of People
  Rooms                       - 1 +
  Adult                       - 1 +
  Children                    - 0 +
  
  Where + and - are clickable buttons
  
  The rooms number will lie between 1 and 5
  and everytime when user click on + button of rooms it will increase th equantity of adult 
  and adult value will never less than rooms number
  
  each room can have 4 members (both Adult and Children)
  
  when room number decreases we are checking the numbers in Adult and Children 
    if sum of both fileds is greater than 4*rooms 
       we are reducing the children count and then if required Adult count
       
 For all the caluclation purpose i used three variables:
   1. var rooms_va =1
   2. var Children_va =0
   3. var adult_var = 1
room_va for rooms count reference
Childre_va for chilren count reference
adult_va for adult count reference




To run the program:

just copy the code to anyfile.html format and open the file with any browser
