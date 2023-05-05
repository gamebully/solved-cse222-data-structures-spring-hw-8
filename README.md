Download Link: https://assignmentchef.com/product/solved-cse222-data-structures-spring-hw-8
<br>
<h1>Description</h1>

We have a group of people in which an ordered popularity relation is defined between person pairs. If there exist a relation such that  (P1,P2)  this means that A thinks that B is popular. The relation is transitive which means that if  the relations (P1,P2) and (P2,P3) exist, than (P1,P3) also exist event if it is not specified by the input pairs. You are supposed to write a Java program which finds the people who are considered popular by every other person.

<h1>Input (input.txt)</h1>

<ul>

 <li>Line 1: Two space-separated integers, N (number of people) and M (number of ordered relations)</li>

</ul>




<ul>

 <li>Lines 2..1+M: Two space-separated numbers P1 and P2, meaning that P1 thinks P2 is popular.</li>

</ul>

<h1>Output</h1>

* Line 1: An integer which represents the number of people who are considered popular by every other person.

<h1>Sample Input</h1>

3 3

<ul>

 <li>2</li>

 <li>1</li>

</ul>

2 3

<h1>Sample Output</h1>

1