Download Link: https://assignmentchef.com/product/solved-cse6643-homework-2
<br>
Notice: For the computational problems, you must design your own ways, such as using tables and plots etc, to present the results you obtain. And you must show the procedure you take, and explain the results you get, and draw conclusions if you have any. Computer code is not considered as an explanation. Please upload your code in T-square, and return your HW in class on or before the Due date.

<ul>

 <li><strong>Problem 1</strong>: Show that (1+ ) and (1+ when</li>

 <li><strong>Problem 2</strong>: Consider a matrix</li>

</ul>

<em>.</em>

<ul>

 <li>Compute <em>A</em><sup>−1 </sup>and</li>

 <li>Given examples for <em>b,δb,x </em>and <em>δx </em>satisfying</li>

</ul>

<em>Ax </em>= <em>b,        A</em>(<em>x </em>+ <em>δx</em>) = <em>b </em>+ <em>δb,</em>

such that  is small, but  is large.

<ul>

 <li><strong>Problem 3</strong>: Given <em>x </em>∈ C<sup>2</sup>, determine a unitary matrix of the form</li>

</ul>

<em> ,</em>

where <em>c </em>∈ R and <em>c</em><sup>2 </sup>+ |<em>s</em>|<sup>2 </sup>= 1, such that the second component of <em>Q</em><sup>∗</sup><em>x </em>is zero.

<ul>

 <li><strong>Problem 4</strong>: Modify the Householder QR algorithm so that it can efficiently handle the case when <em>A </em>∈ R<em><sup>m</sup></em><sup>×<em>m </em></sup>has lower bandwidth <em>p </em>and upper bandwidth <em>q</em>. Present you algorithm in a pseudo code fashion, and compute its computational cost in terms of <em>m</em>. Write your own code to perform your algorithm. Use your code to compute the QR factorization for a <em>m</em>×<em>m </em>symmetric Toeplitz matrix with first column given by [10<em>,</em>3<em>,</em>2<em>,</em>1<em>,</em>0<em>,</em>·· <em>,</em>0]<em><sup>T</sup></em>. Vary <em>m </em>to confirm your estimate of the computational cost.</li>

 <li><strong>Problem 5</strong>: The following experiments are on random matrices and their QR factorizations. Hint: you may want to read Lecture 9 in the reference book by Trefethen and Bau before you work on this part of the project.

  <ul>

   <li>Design a procedure to create a random matrix <em>A </em>of dimension <em>n</em>×<em>n </em>with singular values given as 3<sup>−1</sup><em>,</em>3<sup>−2</sup><em>,</em>·· <em>,</em>3<sup>−<em>n</em></sup>.</li>

   <li>Write your own code for classical Gram-Schmidt and modified Gram-Schmidtalgorithms. Use your code to compute QR factorizations for the matrix <em>A </em>generated in (a). Compare and comment your results. If you find something interesting, you should try to explain it.</li>

   <li>Write your own code for Householder transform and perform it to the matrix <em>A</em>.</li>

  </ul></li>

</ul>

Form the <em>Q </em>matrix from your procedure and comment on the results.

Run your experiments with <em>n </em>= 100, <em>n </em>= 200 and <em>n </em>= 300 respectively. Repeat the experiments for different random matrices.

2