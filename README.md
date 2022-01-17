# Assignment_equalExpert:

How to Run the project:
1. Go to  src/main/java/EqualExpert
2. Right click on TestHotelBookingForm.java class and run as "TestNG" Test
3. See the outcome in TestNG report




Brief Summary of the manual test performed: -

Test 1 – Responsive UI Test

A.      User trying to Save a new booking in the hotel booking form, However the textfield (Firstname, Surname, Price), Dropdown (Deposit), Date picker (Check-in, Check-Out) & Save button are partly out of the user sight.

B.      Webpage elements are not aligned in all different sizes of browser.

Test 2 – Save a new entry to Hotel booking Form

A.      User able to Save a -ve price which is incorrect.

B.      User able to book hotel in the past date which is incorrect.

C.       User has booked hotel for a future date with a +ve price, but application is taking this entry with deposit flag as false.

D.      User could incorrectly be able to flag the Deposit as true although the Price is set to 0

Test 3 – Delete an entry from Hotel booking Form.

A.      User could be able to delete any entry from the booking form. User shouldn’t be allowed to delete booking from other’s entry from the booking form

Test 4 – Data Validation Test

A.      User can enter Firstname, Surname with any character which is incorrect.

B.       Prices fields aren’t rounding off the decimal part.

C.       There is no validation on test data length for every textfield and hence if a user tries saving below set of test data: -

Firstname - Hubert Blaine Wolfeschlegelsteinhausenbergerdorff Sr

Surname - Hubert Blaine Wolfeschlegelsteinhausenbergerdorff Sr

Price – 13.91111117829917827

Deposit – true

Check-in – 2022-01-16

Check- out - 2022-01-16

 

Upon Saving above data, the entry gets overlapped over each-other.

