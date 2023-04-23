Download Link: https://assignmentchef.com/product/solved-ad-homework-batchii-trees-and-algorithms
<br>
Homework Batch II: Trees and Algorithms

<ol>

 <li>Let <em>H </em>be a Min-Heap containing <em>n </em>integer keys and let <em>k </em>be an integer value. Solve the following exercises by using the procedures seen during the course lessons:

  <ul>

   <li>Write the pseudo-code of an in-place procedure RetrieveMax(H) to efficiently return the <u>maximum </u>value in <em>H </em>without deleting it and evaluate its complexity.</li>

   <li>Write the pseudo-code of an in-place procedure DeleteMax(H) to efficiently deletes the <u>maximum </u>value from <em>H </em>and evaluate its complexity.</li>

   <li>Provide a working example for the worst case scenario of the procedure DeleteMax(H) (see Exercise 1b) on a heap <em>H </em>consisting in 8 nodes and simulate the execution of the function itself.</li>

  </ul></li>

 <li>Let <em>A </em>be an array of <em>n </em>integer values (i.e., the values belong to Z). Consider the problem of computing a vector <em>B </em>such that, for all <em>i </em>∈ [1<em>,n</em>], <em>B</em>[<em>i</em>] stores the number of elements smaller than <em>A</em>[<em>i</em>] in <em>A</em>[<em>i </em>+ 1<em>,…,n</em>]. More formally:</li>

</ol>

<em>B</em>[<em>i</em>] = |{<em>z </em>∈ [<em>i </em>+ 1<em>,n</em>]| <em>A</em>[<em>z</em>] <em>&lt; A</em>[<em>i</em>]}|

<ul>

 <li>Evaluate the array <em>B </em>corresponding to <em>A </em>= [2<em>,</em>−7<em>,</em>8<em>,</em>3<em>, </em>−5<em>,</em>−5<em>,</em>9<em>,</em></li>

</ul>

1<em>,</em>12<em>,</em>4].

<ul>

 <li>Write the pseudo-code of an algorithm belonging to <em>O</em>(<em>n</em><sup>2</sup>) to solve the problem. Prove the asympotic complexity of the proposed solution and its correctness.</li>

 <li>Assuming that there is only a constant number of values in <em>A </em>different from 0, write an efficient algorithm to solve the problem, evaluate its complexity and correctness.</li>

</ul>

<ol start="3">

 <li>Let <em>T </em>be a Red-Black Tree.

  <ul>

   <li>Give the definition of Red-Black Trees.</li>

  </ul></li>

</ol>

1

<ul>

 <li>Write the pseudo-code of an efficient procedure to compute the height of <em>T</em>. Prove its correctness and evaluate its asymptotic complexity.</li>

 <li>Write the pseudo-code of an efficient procedure to compute the blackheight of <em>T</em>. Prove its correctness and evaluate its asymptotic complexity.</li>

</ul>

<ol start="4">

 <li>Let (<em>a</em><sub>1</sub><em>,b</em><sub>1</sub>)<em>,…,</em>(<em>a<sub>n</sub>,b<sub>n</sub></em>) be <em>n </em>pairs of integer values. They are lexicographically sorted if, for all <em>i </em>∈ [1<em>,n </em>− 1], the following conditions hold:

  <ul>

   <li><em>a</em><em>i </em>≤ <em>a</em><em>i</em>+1;</li>

   <li><em>a<sub>i </sub></em>= <em>a<sub>i</sub></em><sub>+1 </sub>implies that <em>b<sub>i </sub></em>≤ <em>b<sub>i</sub></em><sub>+1</sub>.</li>

  </ul></li>

</ol>

Consider the problem of lexicographically sorting <em>n </em>pairs of integer values.

<ul>

 <li>Suggest the opportune data structure to handle the pairs, write the pseudo-code of an efficient algorithm to solve the sorting problem and compute the complexity of the proposed procedure;</li>

 <li>Assume that there exists a natural value <em>k</em>, constant with respect to <em>n</em>, such that <em>a<sub>i </sub></em>∈ [1<em>,k</em>] for all <em>i </em>∈ [1<em>,n</em>]. Is there an algorithm more efficient than the one proposed as solution of Exercise 4a? If this is the case, describe it and compute its complexity, otherwise, motivate the answer.</li>

 <li>Assume that the condition of Exercise 4b holds and that there exists a natural value <em>h</em>, constant with respect to <em>n</em>, such that <em>b<sub>i </sub></em>∈ [1<em>,h</em>] for all <em>i </em>∈ [1<em>,n</em>]. Is there an algorithm to solve the sorting problem more efficient than the one proposed as solution for Exercise 4a? If this is the case, describe it and compute its complexity, otherwise, motivate the answer.</li>

</ul>

<ol start="5">

 <li>Consider the select During the lessons, we explicitly assumed that the input array does not contain duplicate values.

  <ul>

   <li>Why is this assumption necessary? How relaxing this condition does affect the algorithm?</li>

   <li>Write the pseudo-code of an algorithm that enhance the one seen during the lessons and evaluate its complexity.</li>

  </ul></li>

</ol>

2