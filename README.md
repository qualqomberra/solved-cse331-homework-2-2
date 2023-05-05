Download Link: https://assignmentchef.com/product/solved-cse331-homework-2-2
<br>
In this assignment you will write a MIPS assembly program and test it using MARS instruction set simulator.

<strong>Definition: </strong>This program takes one input from an input file, this is an integer array. This program finds a sequence according to increasing order, this program can find more than one sequence but has to return only one sequence that has a maximum length. The outputs of the program are the sequence and the length of the array, the outputs should be written the file.

<strong>Example: </strong> Array_inp: [3, 10, 7, 9, 4, 11],  Array_outp: [3, 7, 9, 11] size = 4       Let’s examine program inner results:

<ul>

 <li>candidate sequence : [10,11] , size = 2</li>

 <li>candidate sequence : [3,7,9,11] , size = 4</li>

 <li>candidate sequence : [3,10,11] , size = 3</li>

 <li>candidate sequence : [7,9,11] , size = 3</li>

 <li>candidate sequence : [4,11] , size = 2</li>

</ul>

The inps/outps of the program have to read/write a text file. Showing inner results in console will bring extra points.

You need to write and explain your pseudocode in report file, you have to add time and space complexity. If you add some optimization parts/tricks, please explain in the report file.