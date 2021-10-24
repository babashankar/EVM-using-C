# EVM-using-C
An Electronic voting machine simulator using C

The project is divided into few parts


1.The program first asks to enter the information of the participants participating in the election and a symbol(only special characters) for each of them.
Restriction: Any two people taking the two symbol should not be permitted,an error message should be displayed.

2.Entering the voter id present in the csv file
Restriction:A person should vote only once ,if the voted voter id is entered error symbol is displayed.


3.casting the vote- The voter will be allowed to vote a candidate by choosing the symbol.
 Restriction:If wrong symbol is entered error message will be displayed.


4.Displaying option such as
results
difference
finish voting
exit the poll


5.Once the 4th option is entered that is to exit the poll.The candidates information like name,symbol and final number of votes are displayed. And the special thing is that one file for each participant will be displayed containing his details..
