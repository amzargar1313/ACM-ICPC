# Defective Altimeter
## Time Limit: 1 Second      Memory Limit: 65536 KB
A passenger plane is approaching the Mehrabad airport. As the pilot started the landing procedure, he figured out that the *Altimeter is defective and does not display* the altitude correctly. While counting down, the altimeter skips the digit 4 in all positions of the displayed number. For example, if the altimeter is displaying 27550 and the airplane descends one foot the altimeter will display 27539 instead of 27549. (The same problem exists when the airplane ascends). In order to save the lives of people on board, the captain asked if any passenger can help. Being the only programmer in the flight, you are asked to write a program that gets the altitude displayed by the defective altimeter and outputs the actual altitude.

>Input:                                                       
The input includes multiple cases each on a single line case containing one integer between 1 and 999,999,999 which represents the displayed number on the defective altimeter. In the last line of the input you will get a single 0.
---
>Output                          
For each test case, you must provide the actual altitude with the format
---
```
A: B
where A is the altitude displayed on altimeter and B is the actual altitude.
```
```
Sample Input
3
17
0
```
```
Sample Output
3: 3
17: 15
```