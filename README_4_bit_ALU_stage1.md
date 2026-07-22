Description:  

This is a 4 bit ALU unit which is incomplete as of now. The aim is to select the decimal numbers from the input section of the encoder and the encoder designed converts the decimal into its equivalent BCD code.
The 4 bit binary number is then used to perform opertaions.



Circuits implemented are:

1.Adder Subtractor circuit- 

  Full adders are used to implement the 4 bit addition and subtraction. A 2:1 mux is used to select between the operations.

  Add=0 and Sub=1
 Logical equation is: For addition- Sum= A exor B exor C  Carry= AB + C( A exor B) and Subtraction is performed as A-B= A+(~B+1); the 2's complement method.

                    

                      
  2.Multiplier circuit-

  Multipiler was designed using the normal multiplication logic. The circuit appears to be too big for practical implementation and hence i am planning onto moving to a more practical way of approach.





  Future Challenges:

1.Making the whole circuit synchronized.

2.A proper design for Multiplier and Divider using shift registers and clocks.

3.Implementing a 4:1 mux to choosee between the operations.
