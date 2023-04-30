Download Link: https://assignmentchef.com/product/solved-metcss521-homework4
<br>



<strong>4.7.1:</strong>   Given a constant list of integers in the range 1 to 10 inclusive, <strong>use list comprehension</strong> (no explicit loops) to:

<ul>

 <li>find the sum of the even integers in list L.</li>

 <li>find the sum of the odd integers in list L.</li>

</ul>

Example of Output:Evaluating the numbers in: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10Even: 30Odd: 25

<strong>4.7.2:</strong>   Given a constant list of integers, write Python code to generate a new list with same number of elements as the original list such that each integer in the new list is the sum of its nearest neighbors and itself from the original list. Print both lists with descriptions.

Example of Output:Input List: [10, 20, 30, 40, 50]Result List: [30, 60, 90, 120, 90

<strong>Chapter 9 Exercises</strong>

<strong>4.9.3    </strong>Start with 2 constant lists. One with first names and another of last names.

First validate that both lists are the same size and if not, exit with an error message.

Use zip to create a dictionary with the keys as the last names and the values as the first names. Print the generated dictionary with an appropriate description.

Example of Output:First Names: [‘Jane’, ‘John’, ‘Jack’]Last Names: [‘Doe’, ‘Deer’, ‘Black’]Name Dictionary: {‘Doe’: ‘Jane’, ‘Deer’: ‘John’, ‘Black’: ‘Jack’}




<strong>4.9.4:</strong>   Using my_dict = {a’:15, ‘c’:18, ‘b’:20}, write a program to:

<ol>

 <li>print all the keys.</li>

 <li>print all the values.</li>

 <li>print all the keys and values pairs.</li>

 <li>print all the keys and values pairs in order of key.</li>

 <li>print all the keys and values pairs in order of value.</li>

</ol>

<em>* Ordering may be ascending or descending</em>

Example of Output (showing alternative ways <strong>you might choose</strong> to print lists and dictionaries):a. Keys: [‘a’, ‘c’, ‘b’]b. Values: 15, 18, 20c. Key value pairs: a: 15, c: 18, b: 20d. Key value pairs ordered by key: [(‘a’, 15), (‘b’, 20), (‘c’, 18)]e. Key value pairs ordered by value: a: 15, c: 18, b: 20

<strong>4.9.5:</strong>   Write the following python program.

Assign to a constant variable an English sentence of at least 15 characters.

Print the starting sentence

Create a <strong>dictionary </strong>with the letters as keys and frequency counts as values.Print the dictionary.

Create a <strong>string</strong> of the most common letter(s) in the sentence. In the case of a tie for the most common letter, the string will have all of themPrint the string and the number of times the letter(s) appeared in the sentence

Create a list of the unique letters, with each letter being the repeated number of times it appears in the string. Then print this list as one element per line (a histogram).

Example Output #1The string being analyzed is: “WAS IT A RAT I SAW”1. Sorted dictionary of letter counts: {‘A’: 4, ‘I’: 2, ‘R’: 1, ‘S’: 2, ‘T’: 2, ‘W’: 2}2. Most frequent letter “A” appears 4 times.3. Histogram:AAAAIIRSSTTWW

Example Output #2The string being analyzed is: “WWAS IT A RAT I SAWW”1. Sorted dictionary of letter counts: {‘A’: 4, ‘I’: 2, ‘R’: 1, ‘S’: 2, ‘T’: 2, ‘W’: 4}2. Most frequent letters [‘A’, ‘W’] appear 4 times.3. Histogram:AAAAIIRSSTTWWWW

<strong>4.9.6:</strong>   Create a program that:

<ul>

 <li>prompts a user for a number</li>

 <li>validates the number</li>

 <li>re-prompts on error</li>

 <li>converts the number to words using a dictionary</li>

 <li>prints out the converted numbers as words</li>

</ul>

The program must only have one input command and work for any size positive or negative number.




Decimal point should be converted to ‘point’.

If the user enters commas, tell them to try again without the commas.

Example Output #1Enter a number: 123As Text: One Two Three

Example Output #2Enter a number: -123As Text: Negative One Two Three

Example Output #3Enter a number: 1234.76As Text: One Two Three Four Point Seven Six

Example Output #4 – invalid InputEnter a number: 1,000Please try again without entering commas.Enter a number: 1 thousand“1 thousand” is not a valid number. Please try againEnter a number: 1000.00As Text: One Zero Zero Zero Point Zero Zero