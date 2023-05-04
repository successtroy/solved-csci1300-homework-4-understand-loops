Download Link: https://assignmentchef.com/product/solved-csci1300-homework-4-understand-loops
<br>
<h1>Objectives</h1>

<ul>

 <li>Understand loops</li>

 <li>Understand C++ loops: while loops, for loops, do-while loops</li>

</ul>

You can find <a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45931">hw4 note: loop on Moodl</a>​ <a href="https://moodle.cs.colorado.edu/mod/resource/view.php?id=45931">e</a>.​

<h1>Questions</h1>

<h2>Question 1: Sum even positive numbers</h2>

Write a program that asks for the end value (as ​integer​), and computes the sum of the even numbers from 0 to the value entered, inclusive.

Expected output 1 (​<strong>bold</strong>​ is user input)

Enter a positive number:

<h3>10</h3>

Sum: 30

The file should be named as ​sumEven.cpp​. Don’t forget to head over to the code runner on Moodle and paste your solution in the answer box!

Question 2: Print ​Collatz sequence

The <u>​</u><a href="https://en.wikipedia.org/wiki/Collatz_conjecture">Collatz conjecture</a><u>​</u> defines a sequence as follows: if ​n​ is an even number, then the next value is ​n/2​. If n is odd, then the next value is ​3n+1​. The sequence is conjectured to always reach 1 regardless of the starting number.

Write a program that takes a starting number n and prints the entire sequence, starting with n and ending with 1. Each number should be printed on a new line.

Expected output example (​<strong>bold</strong> is user input)​

<table width="624">

 <tbody>

  <tr>

   <td width="624">Enter a positive number:<strong>10</strong> 10 5168421</td>

  </tr>

 </tbody>

</table>




The file should be named as ​printCollatz.cpp​. Don’t forget to head over to the code runner on Moodle and paste your solution in the answer box!

Question 3): Zootopia

The Zootopia Police Department is recruiting new officers and has come up with an innovative equation to hire. They define hireScore​ as a weighted sum of agility​ ,​ strength​ ,​ and speed.​

hireScore = 1.8 * ​  agility​ + 2.16 * ​ strength ​  +​ 3.24 * speed​

The candidates for this hiring season are foxes, bunnies, and sloths. Chief Bogo has requested you to write a program that takes in these attributes and processes a hireScore​ for the candidate.

The program should provide a menu to choose the anthropomorphic animal. The menu should have the following options:

<ol>

 <li>Fox</li>

 <li>Bunny</li>

 <li>Sloth</li>

 <li>Quit</li>

</ol>

Once an animal is selected, the program should ask the two of the characteristics based on the animal

<ol>

 <li>For fox, take input for agility​ and ​     strength​</li>

 <li>For bunny, take input for agility​ and ​     speed​</li>

 <li>For Sloth, take input for strength​ and ​     speed​</li>

</ol>

Note: You must prompt the user for agility, strength, and speed <strong>in</strong>​<strong> that order</strong>,​ while also <em>skipping </em>​the attribute <em>prompt that does not apply </em>​ ​to the particular animal.

Write a program to compute the hireScore​ ​ based on the inputs using the weighted sum formula. When you compute the hireScore​ ,​ one of the three characteristics would be 0. The computed hireScore​ should​ be displayed on the screen. The menu will run in a loop, continually offering Bogo four options until he chooses to quit. If the choice is not between 1 – 4, then it prints “Invalid option​ ”. When Bogo select option 4, it prints “​ Good bye!​ ”​

Expected output (​<strong>bold</strong>​ is user input)

<table width="624">

 <tbody>

  <tr>

   <td width="624">Select a numerical option:=== menu ===1.  Fox2.  Bunny3.  Sloth4.  Quit<strong>1 </strong>Enter agility:<strong>10.5 </strong>Enter strength: <strong>20.1 </strong>Hire Score: 62.316Select a numerical option:=== menu ===1.  Fox2.  Bunny3.  Sloth4.  Quit<strong>2 </strong>Enter agility:<strong>10.1 </strong>Enter speed:<strong>30.0 </strong>Hire Score: 115.38Select a numerical option:=== menu ===1.  Fox2.  Bunny3.  Sloth4.  Quit<strong>10 </strong>Invalid optionSelect a numerical option:=== menu ===1.  Fox2.  Bunny3.  Sloth4.  Quit<strong>4 </strong>Good bye!</td>

  </tr>

 </tbody>

</table>




The file should be named as ​zootopia.cpp​. Don’t forget to head over to the code runner on Moodle and paste your solution in the answer box!




<strong> </strong>

<h2>Question 4(10pt): Dream house</h2>

You have graduated from CU Boulder and have a great job! You moved to Seattle and decided to save money to buy a house. Write a program to determine how many months it will take you to save enough money to make the down payments given the following assumptions:

<ul>

 <li>The portion of the cost needed for a down payment is 25% (0.25)</li>

 <li>Since you just graduated, the current saving is 0</li>

 <li>Assume you invest your current savings wisely. At the end of each month, you receive additional funding, ​<em>currentSaving</em>​ * r / 12 where r = 0.04. (r is an annual rate, so we divided it by 12)</li>

 <li>At the end of each month, your savings will increase by the return of the investment and the portion of the salary.</li>

</ul>




Your program asks:

<ol>

 <li>The starting annual salary (in ​double​)</li>

 <li>The portion of the salary you save each month for a down payment (in ​double​) 3. The cost of your dream house (in ​double​)</li>

</ol>




Expected output 1 (​<strong>bold</strong>​ is user input)

Enter your annual salary:

<strong>120000 </strong>

Enter the percent of your salary to save, as a decimal:

<h2>.10</h2>

Enter the cost of your dream home:

<h3>1000000</h3>

Number of months: 183




The file should be named as ​dreamHouse.cpp​. Don’t forget to head over to the code runner on Moodle and paste your solution in the answer box!










<h3>Question 5(15pt): Count matches</h3>

A ​<a href="https://en.wikipedia.org/wiki/Substring">substring</a>​ refers to a string that is a continuous segment of a larger string. The list of all substrings of the string, “​apple​”, would be:

<ul>

 <li>“​apple​”,</li>

 <li>“​appl​”, “​pple​”,</li>

 <li>“​app​”, “​ppl​”, “​ple​”,</li>

 <li>“​ap​”, “​pp​”, “​pl​”, “​le​”,</li>

 <li>“​a​”, “​p​”, “​p​”, “​l​”, “​e​”</li>

 <li>“”</li>

</ul>




Write a program that asks for two strings: a string where the substring is searched and substring whose occurrences is to be found. Then, it displays the number of matches.

Expected output 1 (<strong>bold</strong>​ is user input)​

Enter the search string:

<strong>mississippi </strong>

Enter the substring to be searched:

<h2>si</h2>

Number of occurrences: 2




Expected output 2 (<strong>bold</strong>​ is user input)​

Enter the search string:

<strong>mississippi </strong>

Enter the substring to be searched:

<h2>ipp</h2>

Number of occurrences: 1




The file should be named as countMatches.cpp​  . Don’t forget to head over to the code​              runner on Moodle and paste your solution in the answer box!




<h3>Question 6(15pt): Print an alphabetical triangle</h3>

Write a program that takes the height of the triangle, then it prints the triangle like below.




Expected output 1 (<strong>bold</strong>​ is user input)​

<table width="624">

 <tbody>

  <tr>

   <td width="624">Enter the height:<strong>4 </strong>abcd efg hi j</td>

  </tr>

 </tbody>

</table>




Expected output 2 (<strong>bold</strong>​ is user input)​

<table width="624">

 <tbody>

  <tr>

   <td width="624">Enter the height:<strong>10 </strong>abcdefghij klmnopqrs tuvwxyza bcdefgh ijklmn opqrs tuvw xyz ab c</td>

  </tr>

 </tbody>

</table>




The file should be named as printTriangle.cpp​               . Don’t forget to head over to the code​              runner on Moodle and paste your solution in the answer box!

<strong> </strong>

<h3>Extra credit Question (10pt): Print diamond</h3>

Write a program that takes the side length of the diamond, then it prints the diamond like below.




Expected output 1 (<strong>bold</strong>​ is user input)​

Enter the length:

<strong>4 </strong>

*

***

*****

*******

*****

***

*




Expected output 2 (<strong>bold</strong>​ is user input)​

Enter the length:

<strong>2</strong>

*

***

*


