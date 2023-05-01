Download Link: https://assignmentchef.com/product/solved-ccucd-project-3-a-simple-c-interpreter
<br>



<strong> </strong>In this project, you should implement a C interpreter. The supported input file should at least contain the following features:

<ul>

 <li>integer and floating-point data types: int, float.</li>

 <li>Statements for arithmetic computation. (ex: a = b+2*(100-1)) (3) Comparison expression. (ex: a &gt; b)</li>

 <li>if-then-else program construct.</li>

 <li>printf() function with one/two parameters. (support types: %d, %f)</li>

 <li>scanf() (support types: %d, %f)</li>

</ul>

<strong> </strong>

The following is a sample C program (input file):

<ol>

 <li>void main()</li>

 <li>{</li>

 <li>int num;</li>

 <li>float s;</li>

 <li></li>

 <li>printf(“Please enter a number:”); 7. scanf(“%d”, &amp;num);</li>

 <li></li>

 <li>if (num &gt; 10) {</li>

 <li>s = 3 * (num + 3.14);</li>

 <li>} else {</li>

 <li>s = num * (num – 3.14);</li>

 <li>}</li>

 <li></li>

 <li>printf(“The result is %f
”, s);</li>

 <li>}</li>

</ol>




In your hand-in report, you need to have the followings:

<ul>

 <li><strong>Describe the C subset supported by your interpreter. </strong></li>

 <li>Give a set of testing programs which can illustrate the features of your interpreter. (at least 3 test programs)</li>

 <li>Use the “<strong>ANTLR</strong>” to help you develop your interpreter.</li>

 <li>You can use <strong>Java</strong> or <strong>other programming languages</strong> to write your interpreter. (Java is recommended)</li>

 <li>Please ensure your program can be executed under the <strong>mcore8</strong> or</li>

</ul>

1

Compiler Design

<strong>linux.cs.ccu.edu.tw</strong> workstation.




3