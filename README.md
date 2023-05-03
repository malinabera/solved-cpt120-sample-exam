Download Link: https://assignmentchef.com/product/solved-cpt120-sample-exam
<br>
<h1>Q1</h1>

<table width="720">

 <tbody>

  <tr>

   <td width="720">public class Q1 {public static void main(String[] args){       int s=___________________;       if (s&lt;5)          s=5;       String answer=””;       int a=1;       while(a&lt;s){          answer=a+answer;          if (a%3==0)answer=”
”+answer;          a=a+1;       }            System.out.println(answer);}}</td>

  </tr>

 </tbody>

</table>

In the Java program above, fill in the blank with a value that can be assigned to the variable ‘s’ then write only the output of the program below:

(Tip: Use the reverse/non-printed side of this exam paper for any rough work)

<h1>Q2</h1>

Fill in the blanks and complete the code below so that the code is valid and runs as described in the comments and the output message. You must use primitive data types over class types when possible. (Tip: Use the reverse/non-printed side of this exam paper for any rough work).

<table width="720">

 <tbody>

  <tr>

   <td width="720">public class Q2{public static void main(String[] args){ // A data type for a number with a decimal point and a compatible value____________________ val1=____________________;// A whole number type and a compatible value____________________ valB=____________________;// A data type for a number with a decimal point that is different to val1’s type.____________________ val2=valB;// A data type for a number with a decimal point but generates an error.____________________ val3=val1*val2;System.out.println(val1+” “+val2+” “+val3);}}</td>

  </tr>

 </tbody>

</table>

Which line of code above would generate a compilation error if completed according to the requirements stated in the comments?

Re-write the above line of code to rectify the error:

Write the output of the program when the corrected code is used:

<h1>Q3</h1>

Consider the Tower class below which has already been implemented and is available for you to use:

Tower class: A Tower object cannot be created without a <em>x</em> and <em>y</em> coordinates (each a whole number between 0-9 inclusive) and a <em>type</em>. The <em>type </em>indicates whether it is a digital signal tower or an analogue signal tower. It has accessors for the information mentioned above. Only its constructor and the said accessors methods can be accessed by other classes.

Following the Map class requirements below and by using the best object-oriented design guidelines and practices taught in the unit, write the relevant code in the designated spaces provided.

Map class: A Map object has an array of Tower objects. A Map object cannot be created without a name value and a value for the maximum array size. A Map object also has the methods addTower, showTowerMap and showUserInterface. When a Map object is instantiated, it must also call the showUserInterface method (assume the showUserInterface method is already present). Aside from the methods, no other component of this class should be accessible by other classes.

The addTower method takes the minimum information required for creating a Tower object as its parameters. If a Tower object with the same coordinates does not exist in the Tower array of the Map object, a new Tower object is added to the array, if possible. There must not be multiple objects with the same coordinates in the array.

The showTowerMap method displays displays a grid of the Tower placements with “dots” to denote where there is no tower and a D or an A to denote digital or analogue tower respectively. E.g. if there is a digtal tower at 0,5 (x,y) and analogue towers at 2,3 and 5,2, this method would display in the following format:

…..D…

………

…A…..

………

………

..A……

………

………

……… ………

Note: Use only standard arrays in Java (e.g. avoid ArrayList, etc.). You must not use break, continue, System.exit(). Use only while loops for repetition. When possible, you must use concepts covered in standard class materials over others. Use the reverse/non-printed side of this exam paper for any rough work.

Write below the code for any member variable declarations of the Map class.

Write below the code for any definitions and implementations of a constructor of the Map class:

Write below the code for the definition and implementation of the showTowerMap method of the Map class: