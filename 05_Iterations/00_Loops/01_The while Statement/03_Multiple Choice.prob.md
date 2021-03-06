>>Consider the following code segment:
<pre><code>int varOne = 3;
int varTwo = 2;
int varThree = 0;
while (varOne &lt;= 5){
  varThree += varOne % varTwo;
  varOne++;
  varTwo++;
}
</code></pre>
<p>What is the value of <code>varThree</code> after the code is executed?</p><<

( ) 1 {{Incorrect because the value of <code>varThree</code> will be 3. View the step-by-step solution for the question by selecting the correct answer, 3.}}
( ) 111 {{Incorrect because the value of <code>varThree</code> will be 3. View the step-by-step solution for the question by selecting the correct answer, 3.}}
( ) 2 {{Incorrect because the value of <code>varThree</code> will be 3. View the step-by-step solution for the question by selecting the correct answer, 3.}}
(x) 3 {{Correct because it accurately represents what the while loop does and the number of times <code>varThree += varOne % varTwo</code> is executed.
<p>The process is shown below. Use the comments to guide you through each step:</p>
<p>When varOne = 3,<br/>
<code>varOne &lt;= 5</code> // results in true<br/>
<code>varThree += varOne % varTwo</code> // varThree += 1<br/>
<code>varOne++</code> // varOne = 4<br/>
<code>varTwo++</code> // varTwo = 3</p>
<p>When varOne = 4,<br/>
<code>varOne &lt;= 5</code> // true<br/>
<code>varThree += varOne % varTwo</code> // varThree + 1<br/>
<code>varOne++</code> // varOne = 5<br/>
<code>varTwo++</code> // varTwo = 4</p>
<p>When varOne = 5,<br/>
<code>varOne &lt;= 5</code> // true<br/>
<code>varThree += varOne % varTwo</code> // varThree + 1<br/>
<code>varOne++</code> // varOne = 6<br/>
<code>varTwo++</code> // varTwo = 5</p>
<p>When varOne = 6,<br/>
<code>varOne &lt;= 5</code> // false</p>
<p>Therefore, <code>varThree</code> wii equal to 3 after the <code>while</code> loop is run.</p>}}
( ) None of these answers is correct. {{Incorrect because the statements above will compile and run successfully. View the step-by-step solution for the question by selecting the correct answer, 3..}}

||The while statement only runs 3 times, when <code>varOne = 3</code>, <code>varOne = 4</code>, and <code>varOne = 5</code>. ||
