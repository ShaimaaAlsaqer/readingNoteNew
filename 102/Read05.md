Read: 05 - Operators and Loops
Comparison and logical operators
In the comparison == meaning is equal, != is meaning not equal
In comparison we compare 2 values(number, string and Boolean)
A==A True
A != A false

===
Compare 2 values to check that is it same in datatype and value
!===
Compare 2 values to check that is it not same in datatype and value
‘5’ ===5 False
5 !=== 5 True

(>) greater than
(<) less than
4>3 True
4<3 False

(>=) greater thanor equal
(<=) less than or equal
4>= 3 true
4<=3 false
Logical operation allows you to compare the results of more than one comparison operator
((5<2) &&(2>=3))
5<2 f
2>=3 f
&& meaning and
f and f = f

&& and
(|| ) or  ((2<5) ||  (2<1)) true
! not !(2<1)= !false = true
Loops
1 for
2 while
3 do while

For( I =0; i<10; i++)
{//code goes here}

while (condition) {
  // code goes here
}
Example 
while (i < 10) {
  text += "The number is " + i;
  i++;
}
