<table>
   <thead>
      <tr>
         <th>Page</th>
         <th>Error/Correction</th>
         <th>Notes</th>
         <th>Credits</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>vii</td>
         <td>Replace "expose" with "exposure".</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>5</td>
         <td>In the <code>testFToC</code> method, in the respective <code>assertEquals</code> call, the <code>fToC(40)</code> should instead be <code>fToC(-40)</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>6</td>
         <td>In the <code>testComputeDistance</code> method, all of the <code>assertEquals</code> calls must be prefixed by <code>() -> </code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>7-8</td>
         <td>Example 1.3: change all parameters in <code>slope</code> and <code>yIntercept</code> to be <code>double</code> rather than <code>int</code></td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>8</td>
         <td>In the <code>testSlope</code> method, change <code>assertEquals(2, slope(8, 4, 2, 4))</code> to <code>assertEquals(0, slope(8, 4, 2, 4))</code>. Also add a delta of .01 to all tests in <code>testSlope</code> and <code>testYIntercept</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>19</td>
         <td>Example 1.19, there's no reason for this example to be here. It onboards for loops way earlier than they should be talked about.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>23</td>
         <td>The <code>static double stats</code> method should return a <code>String</code>, not a <code>double</code>.</td>
         <td></td>
         <td>Marlena Ames</td>
      </tr>
      <tr>
         <td>26</td>
         <td>Condition <code>if (x != 10 && y != 5) { y += 5; }</code> should be <code>if (x == 10 && y != 5) { y += 5; }</code>.</td>
         <td></td>
         <td>Ty Rimedio</td>
      </tr>
      <tr>
         <td>38</td>
         <td>Example 2.6, the example <code>removeDivThreeChars("CC")</code> should not return <code>"CCC"</code>. The input to the method call and the expected output should be swapped. Change "...are located at positions (note the use of position and not index) are divisible by three." to "...are located at positions (note the use of position and not index) <b>that</b> are divisible by three." </td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>40</td>
         <td>In the second code listing, the <code>remSeqCharsHelper</code> method and calls should be <code>remSeqCharsTRHelper</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>41</td>
         <td>
            The <code>else if (b % 2 == 0)</code> case in the <code>pow</code> method should be:
            <pre><code>
        else if (b % 2 == 0) {
            return pow(n * n, b / 2);
        }
        </code></pre>
         </td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>42</td>
         <td>
            The <code>else if(b % 2 == 0)</code> case in the <code>powTRHelper</code> method should be:
            <pre><code>
        else if(b % 2 == 0) {
            return powTRHelper(n * n, b / 2, acc);
        }
        </code></pre>
         </td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>50</td>
         <td>Example 2.10, the first sentence should instead say, "Let's design an algorithm to determine if a given integer is a Disarium number."</td>
         <td></td>
         <td>Mukund Singh</td>
      </tr>      
      <tr>
         <td>51</td>
         <td>Instead of "The third accumulator, ...", it should say "The second accumulator, ...".</td>
         <td></td>
         <td>Mukund Singh</td>
      </tr>
      <tr>
         <td>51</td>
         <td>The code for <code>isDisariumSR</code> is incorrect. In particular, the accumulator <code>p</code> should store the number of digits and descend down to 1, rather than ascend from 1. One solution is to use the <code>countDigits</code> method from Example 2.9. Another solution is to use <code>Math.floor(Math.log10(n) + 1)</code>.</td>
         <td></td>
         <td>Mukund Singh</td>
      </tr>
      <tr>
         <td>51-52</td>
         <td>The code for <code>isDisariumTR</code> is incorrect. It has the same issue as <code>isDisariumTR</code>.</td>
         <td></td>
         <td>Mukund Singh</td>
      </tr>
      <tr>
         <td>52</td>
         <td>The code for <code>isDisarium</code> is incorrect. It has the same issue as <code>isDisariumSR</code> and <code>isDisariumTR</code>. The method should also be called <code>isDisariumLoop</code>.</td>
         <td></td>
         <td>Mukund Singh</td>
      </tr>   
      <tr>
         <td>54</td>
         <td>Example 2.11: the test case for <code>isPrime(2)</code> should return true because 2 is prime. Change <code>assertFalse(isPrime(2))</code> to <code>assertTrue(isPrime(2))</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>60</td>
         <td>Add the missing ending double quote: <code>"gafia"</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>65</td>
         <td>After the last <code>assertEquals</code>, remove the comma and the last closing parenthesis on the line where its by itself. Add a closing parenthesis and a semicolon.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>67-68</td>
         <td>The <code>FindReplace</code> example has several issues. There are a few missing commas to delimit parameters in the calls to <code>replace</code>. Moreover, the code does not work when the `find` search string is longer than the current substring. So, we need to add the following to the final case analysis:
<br />
<pre style="white-space: pre;"><code>
      // If we reach the end of the string and are in the middle of searching, we append.
      if (pos &gt; 0 &amp;&amp; j &gt;= s.length()) {
        if (pos == find.length()) {
          sb.append(repl);
        } else {
          sb.append(s, i, s.length());
        }
        break;
      }
</code>
</pre>
         </td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>68</td>
         <td>Concatenating two strings together in a loop does not, in fact, produce another integer. It produces a string. The idea behind this explanation is to describe that repeated concatenations is inefficient in loops/recursion due to repeated string copying.</td>
         <td></td>
         <td></td>
      </tr>  
      <tr>
         <td>76</td>
         <td>Exercise 2.34, part (b) description should read: "Design the <code>isFactorionTR</code> tail recursive method, which solves the same problem as part (a), but uses tail recursion."</td>
         <td></td>
         <td>Owen Harris</td>
      </tr>
      <tr>
         <td>78</td>
         <td>In Exercise 2.39, part (a) description should not contain <i>(9 points)</i>. Also, it should not contain <code>List</code>; change this to <code>String</code>. That is, it should return a string of all of the parenthesized strings concatenated together.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>79</td>
         <td>Exercise 2.44 should include a clause saying that methods to make the problem trivial, e.g., <code>Integer.parseInt</code>, are disallowed.</td>
         <td></td>
         <td>Peter Perry</td>
      </tr>
      <tr>
         <td>89</td>
         <td>Example 3.2: the second <code>sumOfDoubles</code> definition should not have a <code>double</code> parameter; it should instead be a <code>double[]</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>91</td>
         <td>Example 3.5: In the <code>LargestIntTester</code> class, all of the <code>assertEquals</code> calls should be prefaced with <code>() -></code></td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>93</td>
         <td>The <code>indexOfLoop</code> method should contain an <code>i++</code> statement after the conditional, otherwise it never terminates.</td>
         <td></td>
         <td>Jonathan Vidal</td>
      </tr>
      <tr>
         <td>100</td>
         <td>The footnote about Java not having support for ragged/jagged arrays is incorrect. Java does support these. Therefore, the sentence preceding the footnote should read as, "To get the number of columns, because we know that A is an array of one-dimensional arrays, we use A[i].length, where i is the ith row of the two-dimensional array.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>101</td>
         <td>Example 3.11: There is no <code>assertArrayEquals</code> method for multi-dimensional arrays. To circumvent this, we can use <code>Arrays.deepEquals</code> and assert that it returns <code>true</code>. The <code>Arrays.deepEquals</code> method compares the <i>contents</i> of multi-dimensional arrays.</td>
         <td></td>
         <td></td>
      </tr>      
      <tr>
         <td>105</td>
         <td>The semicolon after the first <code>assertEquals</code> call inside <code>testLogSaw</code> should instead be a comma.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>108</td>
         <td>"Like many algorithm that makes two subsequent recursive calls..." => "Like many algorithms that make multiple, subsequent recursive calls..."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>108</td>
         <td>Dynamic "programmingg" => Dynamic programming</td>
         <td></td>
         <td>Lillie Donato</td>
      </tr>
      <tr>
         <td>113</td>
         <td>In the <code>getFromList</code> method, the <code>return (idx &lt; 0 || &gt;= upperBound) ? -1 : list[idx];</code> should include the <code>i</code> variable in front of the <code>&gt=</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>121</td>
         <td>Example 3.25: The first two <code>assertEquals</code> statements in the <code>testTakeEvens</code> method should be terminated with commas and not semicolons.</td>
         <td></td>
         <td></td>
      </tr>      
      <tr>
         <td>122</td>
         <td>The <code>t1</code> and <code>t2</code> declarations should be instantiated to <code>new ArrayList&lt;&gt;(List.of(...))</code>, because just using <code>List.of</code> creates an immutable list.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>122</td>
         <td>The semicolons after the calls to <code>filterQuarters</code> and <code>assertEquals</code> should be changed to commas in the <code>assertAll(...)</code> block.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>127</td>
         <td>In the <code>maxPathSizeHelper</code> method, change instances of <code>level</code> and <code>idx</code> to <code>l</code> and <code>i</code> respectively.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>133</td>
         <td>
            In Example 3.30, the code for instantiating a <code>Comparator</code> inside the <code>priorityByP</code> method should be:
            <pre><code>
      static PriorityQueue<String> priorityByP() {
        Comparator<String> c = new Comparator<>() {
          @Override
          public int compare(String s1, String s2) { /* TODO. */ }
        };
      }
      </code></pre>
         </td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>136</td>
         <td>In Figure 3.9, the <code>add</code> method should instead say, "If <code>e</code> is not in <code>S</code>, it returns <code>true</code>; otherwise, it returns <code>false</code>."</td>
         <td></td>
         <td>Dylan Waintraub</td>
      </tr>
      <tr>
         <td>136</td>
         <td>In Figure 3.9, the caption should read, "Useful <code>Set</code>-based Methods." rather than "Useful <code>Sets</code>-based Methods."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>140</td>
         <td>In Figure 3.10, the <code>size</code> method should instead say that it returns the number of logical elements in the "map" rather than "set".</td>
         <td></td>
         <td>Dylan Waintraub</td>
      </tr>
      <tr>
         <td>145</td>
         <td>Step 4 in the code snippet should be Step 3.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>147</td>
         <td>Example 3.38: In the <code>testIterator</code> method, change the semicolon after the first <code>assertEquals</code> statement to a comma.</td>
         <td></td>
         <td></td>
      </tr>           
      <tr>
         <td>148</td>
         <td>
            The code snippet of Example 3.40 should be as follows (note that the errata omits the comments due to a strange Markdown bug):
            <br />
            <pre style="white-space: pre;"><code>
     import java.util.ArrayDeque; <br /><br />
     import java.util.Deque; <br />
     import java.util.Iterator; <br />
     import java.util.List; <br />
     import java.util.Stack; <br />
     class StackPrinter { <br />
       public static void main(String[] args) { <br />
         List&lt;Integer&gt; L = List.of(10, 20, 30, 40, 50); <br />
         Stack&lt;Integer&gt; S = new Stack&lt;&gt;(); <br />
         for (int x : L) { S.push(x); } <br />
         for (int x : S) { System.out.println(x); } <br />
         Deque&lt;Integer&gt; D = new ArrayDeque&lt;&gt;(); <br />
         for (int x : L) { D.push(x); } <br />
         for (int x : D) { System.out.println(x); } <br />
       } <br />
     }</code></pre>
         </td>
         <td></td>
         <td>Joshua Park</td>
      </tr>
      <tr>
         <td>155</td>
         <td>This isn't an error, but immediately preceding Example 3.46 should be an explanation of intermediate and terminal operations. Here is such an explanation: "In addition to talking about the higher-order functions, we should also briefly describe the difference between intermediate and terminal opreations. An <em>intermediate operation</em> is an operation that returns a stream. For example, <code>map</code>, <code>iterate</code>, <code>limit</code>, and so forth are all intermediate operations because they delay their evaluation by creating a stream that <em>represents</em> the evaluation. Only upon using a <em>terminal operation</em> do those streams execute/evaluate. Examples of terminal operations include <code>toList</code>, <code>reduce</code>, and <code>forEach</code>, because they ultimately perform the last operation on a (sequence of) streams and do not themselves produce a stream. (They, instead, produce non-stream values or have resulting side-effects.)"</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>157</td>
         <td>In Example 3.47, in between the sentence, "...works it folds over the list/stream..." add a semicolon immediately after the word "works".</td>
         <td></td>
         <td></td>
      </tr>
      </tr>
      <tr>
         <td>157</td>
         <td>In the footnote, change <code>foldr</code> to <code>foldl</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>159</td>
         <td>Example 3.49: the third assert statement inside the <code>OptionalTester</code> class, namely <code>assertEquals(42, ...)</code> should end with a comma and not a semi-colon.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>162</td>
         <td>In the last sentence of the first paragraph of the page, change <code>&lt;T super Integer&gt;</code> to <code>&lt;? super Integer&gt;</code></td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>166</td>
         <td>In Figure 3.14, the figure title should be changed from "Teaching Java Binary Search Trees" to "Learning Java Binary Search Trees."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>167</td>
         <td>The semicolons after the calls to <code>assertNull</code> and <code>assertEquals</code> should be changed to commas in the <code>assertAll(...)</code> block.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>169</td>
         <td>The semicolons after the calls to <code>assertEquals</code> should be changed to commas in the <code>assertAll(...)</code> block.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>170</td>
         <td>The semicolons after the calls to <code>assertEquals</code> should be changed to commas in the <code>assertAll(...)</code> block.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>174</td>
         <td>Exercise 3.18, the sliding window result should be {{1, 2}, {3, 4}, {5, 6}, {7}}. In the book, it is missing a comma between {1, 2} and {3, 4}.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>176</td>
         <td>The third example in Exercise 3.24 should have the 11 changed to a 1. The description should also change 1 + 4 + 4 = 9 to 4 + 1 + 4 = 9.</td>
         <td></td>
         <td>Josh Rudnik</td>
      </tr>
      <tr>
         <td>185</td>
         <td>
            Exercise 3.65 should say, "In particular, we have a 2D array of strings whose first row contains column headers to a database. Examples of such columns may be 'ID', 'Name', 'Age', 'Salary', and so forth." The last sentence of the first paragraph should be removed as there is no context. <br /> <br />In the second paragraph, change the last few words to "...returns the data from the rows that satisfy the criteria enforced by the command." <br /> <br />Change the definition of a <code>Command</code> to <code>A Command is "SELECT &lt;count&gt; &lt;header&gt; WHERE &lt;predicate&gt;"</code>.<br /> <br />Update the third paragraph to say "The <code>SELECT</code> command receives a <code>&lt;count&gt;</code> and a <code>&lt;header&gt;</code> to designate that the command should return 
            <math>n</math>
            rows with data from the <code>&lt;header&gt;</code> column. An asterisk can be used to select all rows in the database." Your implementation should be flexible enough to work with any arbitrary column over the database. (You may assume that the input <code>&lt;header&gt;</code> is a valid column in the database, but it cannot be hard-coded to fit only a particular set of database columns, e.g., <code>"ID"</code>, <code>"Name"</code>, and so forth.)<br /> <br />Finally, the last <code>'%S%</code> should have a closing single quote: <code>'%S%'</code>.
         </td>
         <td></td>
         <td>Lucas Carreira</td>
      </tr>
      <tr>
         <td>186</td>
         <td>Exercise 3.66, part (d) should say, "...assign the character literal <code>'0'</code>, then loop over...".<br /> <br />In the same part, change the use of <code>extendPath</code> to <code>extPath</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>195</td>
         <td>In the sentences starting with "Going from the simplest to the most complex, ...", rephrase the following sentences to say, "Subroutines and procedures are sets of instructions that can be jumped to and may receive parameters. The term subroutine is, for the most part, outdated. Functions are procedures that can receive parameters and return values. Methods are functions that belong to a class."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>198</td>
         <td>In the <code>testPointRandom</code> method, the semicolons after the calls to <code>assertEquals</code> should be changed to commas in the <code>assertAll(...)</code> block.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>200-201</td>
         <td>At the bottom of the page, it says that "we should include all instance variables of the object to designate that all the properties affect the object's hash code." This is not true; we should include the necessary information to compute an object's hash code. Including <i>all</i> of the instance variables can be problematic, particularly with circular memory references.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>202</td>
         <td>Example 4.8: in the <code>testPizzaOrder</code> method, the second <code>assertEquals</code> statement should be terminated by a comma.</td>
         <td></td>
         <td></td>
      </tr>           
      <tr>
         <td>210</td>
         <td>Change all occurrences of <code>.NAME</code> to <code>.TITLE</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>213</td>
         <td>Example 4.11: In the <code>testVideoGameStoreRent</code> method, all of the <code>assertEquals</code> statements should have their semicolons replaced with commas.</td>
         <td></td>
         <td></td>
      </tr>           
      <tr>
         <td>216</td>
         <td>Add a comma after the closing parenthesis on <code>assertEquals(3, new Board(2, 3, BOARD).getCols())</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>224</td>
         <td>In the <code>testSetX()</code> method, the <code>assertEquals(100, p2.getX())</code> should have a comma after.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>234</td>
         <td>Near the end of the page, we say that a private class can only ever be static. This is not correct. The footnote should also be removed.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>235</td>
         <td>This part of the example should not be in this section; it should be moved to the end of section 4.3 on interfaces. Regardless, change "...of the iterator superclass." to "...of the iterator class."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>235-236</td>
         <td>In the code listing with <code>DoublyLLIterator</code>, the <code>hasNext</code> and <code>next</code> methods should be marked as <code>public</code> because they are inherited from an interface.</td>
         <td></td>
         <td></td>
      <tr>
      <tr>
         <td>239</td>
         <td>Example 4.21, the citation of "McCarthy (1962)" should be "(McCarthy, 1962)."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>241</td>
         <td>Example 4.22, the <code>new List</code> line should read <code>new LinkedList</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <td>244</td>
      <td>The sentence containing, "Instantiating a variable as an interface type...subtype is a form of polymorphism" should read "Initializing a variable as an interface type, then instantiating it as a subtype is a form of polymorphism."</td>
      <td></td>
      <td>Elliot Rubinstein</td>
      </tr>
      <tr>
         <td>253</td>
         <td>The expected value for the final <code>assertEquals</code> in <code>FunctionMapTester</code> should be the empty list (<code>List.of</code>).</td>
         <td></td>
         <td>Elliot Rubinstein</td>
      </tr>
      <tr>
         <td>255</td>
         <td>Example 4.31, The derivative of 3x^2 - 16x + 100 is 6x - 16.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>255</td>
         <td>Example 4.31, add a space between "their" and "(sub-components)".</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>257</td>
         <td>The code "<code>new MonomialExpression("x", 10, 4,</code>" should have a closing parenthesis before the comma: "<code>new MonomialExpression("x", 10, 4),</code>". Remove a closing parenthesis on "<code>new NumberExpression(0)))</code>": "<code></td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>263</td>
         <td>This is the first time that enums are ever used and we shouldn't introduced them here. Change the type to a String and clarify that it can be one of four values: "NORTH", "EAST", "SOUTH", "WEST".</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>263-264</td>
         <td>This is the first time the switch expression is used with -> rather than :. Change this to the latter representation and change the case analysis to use strings instead of the enumeration type.</td>
         <td></td>
         <td></td>
      </tr>
     <tr>
         <td>263-264</td>
         <td>The switch statements should have breaks in all branches.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>269</td>
         <td>At the top of the page, where we say, "...similar to how we counted instances of the <code>Point</code> class in Chapter 4" should instead say, "...in section 4.1."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>269</td>
         <td>Change the first sentence of the last paragraph to, "To keep the conversation interesting, we refrain from overriding the <code>Employee</code> method because there is no significant difference between how an <code>Employee</code> 'works' and one of its subclasses 'works.'"</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>271</td>
         <td>Change "whomever" to "whoever."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>271</td>
         <td>In the <code>testJuniorDeveloperPromotion</code> method, change <code>Developer d = ...</code> to <code>Developer d2 = ...</code>. Also, change the <code>assertFalse</code> invocation to <code>assertFalse(d2.promote() instanceof SeniorDeveloper)</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>274</td>
         <td>Change <code>HourlyEmployee m1 = new Manager("Abby", 30.00)</code> to <code>Manager m1 = new Manager("Abby", 30.00)</code>. This design choice unfortunately violates Liskov's substitution principle, but it works.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>276</td>
         <td>Change "...which returns sets to represent the types that a type is vulnerable to or strong against" to "...which return sets to represent the types that an <code>IType</code> is vulnerable to or strong against respectively."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>278</td>
         <td>"... from the subclass contructor" should be "... from the subclass constructor".</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>280</td>
         <td>In the <code>Archmage</code> code listing, the <code>Set&lt;Type&gt; getTypes()</code> method return type should be <code>Set&lt;IType&gt; getTypes()</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>290</td>
         <td>In the <code>testPrimNode</code> method, all <code>assertEquals</code> statements should end with commas except the last.</td>
         <td></td>
         <td></td>
      </tr>            
      <tr>
         <td>298</td>
         <td>Exercise 4.5, part (d), step (ii) should say, "If u does not exist or t is not the title of a playlist authored by u, return false."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>300</td>
         <td>Exercise 4.8: "This question has six parts" should be "This question has seven parts."</td>
         <td></td>
         <td>Dylan Waintraub</td>
      </tr>
      <tr>
         <td>307</td>
         <td>Exercise 4.23, the last sentence should say "You cannot use <code>StringBuilder</code> or the older <code>StringBuffer</code> classes in your implementation."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>321</td>
         <td>Exercise 4.57 part (a), the example <code>new BigInt(0000420000)</code> should instead be <code>new BigInt("0000420000")</code>.</td>
         <td></td>
         <td>Kashi Kumar</td>
      </tr>
      <tr>
         <td>321</td>
         <td>Exercise 4.57 part (b), the example <code>new BigInt("-42").equals(new BigInt("-42"))</code> says that it returns <code>false</code>. Obviously, this is incorrect, and the example should be changed to <code>new BigInt("-42").equals(new BigInt("42"))</code>. Note the sign change on the second <code>BigInt</code> instance.</td>
         <td></td>
         <td>Owen Harris</td>
      </tr>
      <tr>
         <td>322</td>
         <td>Exercise 4.57 part (j), the <code>mulPositive()</code> should receive a <code>BigInt</code> as a parameter.</td>
         <td></td>
         <td>Jason Wang</td>
      </tr>
      <tr>
         <td>322</td>
         <td>Exercise 4.58, the sentence containing, "...as upper0cased letters..." should be "...as upper-cased letters..."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>325</td>
         <td>Exceptions are not, themselves, effect <i>handlers</i>. Exceptions are control-flow operators that identify events that occur at runtime.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>325</td>
         <td>Change the last sentence of the paragraph at the start of section 5.1 to, "We will discuss several different exceptions by categorizing them into one of two types: unchecked versus checked exceptions."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>327</td>
         <td>Remove the last parenthesis ')' and semicolon after the <code>assertDoesNotThrow</code>call. Add a closing parenthesis ')' and a semicolon after the <code>assertThrows</code> call in the <code>assertAll(...)</code> block.</td>
         <td></td>
         <td></td>
      </tr>
     <tr>
         <td>328</td>
         <td>Example 5.3: after the fourth <code>assertDoesNotThrow</code> invocation, add a comma.</td>
         <td></td>
         <td></td>
      </tr>
     <tr>
         <td>328</td>
         <td>Example 5.4: change everything after "... is an invalid cast..." to "... is an invalid and results in the <code>ClassCastException</code> runtime exception. This is because <code>Integer</code> and <code>String</code> share no discernible inheritance relationship, i.e., <code>Integer</code> is not a superclass/subclass of <code>String</code>, nor vice-versa.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>329</td>
         <td>Example 5.6, replace "an parameter" with "a parameter." This entire example is botched and should be rewritten/omitted. As is, it does not convey the utility of creating a custom exception very well, nor should it use <code>Scanner</code> to demonstrate that capability.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>330</td>
         <td>
            The code snippet of Example 5.7 should be as follows (note that the errata omits the comments due to a strange Markdown bug):
            <br />
            <pre style="white-space: pre;"><code>
import java.io.IOException; <br />
import java.io.FileNotFoundException; <br />
import java.io.FileInputStream; <br />
 <br /> <br />
class FileInputStreamExample { <br />
 <br /> <br />
  public static void main(String[] args) { <br />
    FileInputStream fis = null; <br />
    String inFile = "file1.in"; <br />
    try { <br />
      fis = new FileInputStream(inFile); <br />
      try { <br />
        // Read in data byte-by-byte. <br />
        int val = -1; <br />
        while ((val = fis.read()) != -1) {  <br />
          System.out.print(val);  <br />
        } <br />
      } finally { <br />
        fis.close(); <br />
      } <br />
    } catch (FileNotFoundException ex) { <br />
      System.err.printf("main: could not find %s\n", inFile); <br />
    } catch (IOException ex) { <br />
      System.err.printf("main: I/O err: %s\n", ex.getMessage()); <br />
    } <br />
  }  <br />
}</code></pre>
         </td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>331</td>
         <td>The sentence "So, the program reads one byte then prints it to standard output." should instead be "So, the program reads bytes from the file, then prints them to standard output.".</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>332</td>
         <td>The last sentence preceding Example 5.9 should read as "Therefore a <code>FileReader</code> interprets only textual files, i.e., files without an encoding. Examples of files <i>with</i> an encoding include <code>.pdf</code>, <code>.docx</code>, and so forth."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>334</td>
         <td>The parentheses immediately before <code>new</code> in the <code>nonbuffered</code> method are superfluous. Remove both, remove a closing parenthesis before the semicolon, and remove a closing parenthesis before the opening brace on the next line.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>340</td>
         <td>Example 3.15: the returned array should be <code>[3, 14, 66]</code> rather than <code>[3, 14, 46]</code>. The test case should be updated to reflect this as well.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>342</td>
         <td>Change "I/O error" to "I/O problem."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>350</td>
         <td>Exercise 5.4: "... no punctuation exist" should be "... no punctuation exists."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>361</td>
         <td>Change the first sentence in the abstract from, "This section is divided into..." to "This chapter is divided into..."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>362</td>
         <td>It's really not correct to say that, "we have no way of passing the index-to-check." We can, of course, write a standard recursive method that increments a parameter-based index.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>362</td>
         <td>The footnote's last sentence, "Since Java does not support continuations by default, we cannot take this approach" is misleading. This is <i>exactly</i> the approach we take by using exceptions to 'bail out' of the current stack frame context. What we mean when we say, "by default," we mean that Java does not natively support first-class methods in the same way that would allow us to use first-class continuations, which requires tail-call optimization. (See Scheme or Haskell's implementations of continuations for further information.)</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>367</td>
         <td>Remove type parameters: <code>IBinarySearch search = new TailRecursiveBinarySearch();</code>.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>374</td>
         <td>The first sentence of section 6.2.3, "...algorithms that w will discuss." should be "...algorithms that we will discuss."</td>
         <td></td>
         <td>Elliot Rubinstein</td>
      </tr>
      <tr>
         <td>367</td>
         <td>The semicolons after the first two <code>assertEquals</code> calls should be changed to commas in the <code>assertAll(...)</code> block.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>373</td>
         <td>
            The functional implementation that is listed in the book uses <code>Collections.swap</code>, which is not functional. Here is the correct implementation:
            <br />
            <pre style="white-space: pre;"><code>
  @Override<br />
  public AbstractList<T> selectionSort(AbstractList&lt;T&gt; ls) {<br />
    if (ls.isEmpty() || ls.size() == 1) {<br />
      return ls;<br />
    } else {<br />
      int minIdx = IntStream.range(0, ls.size())<br />
                            .boxed()<br />
                            .min((i1, i2) -> ls.get(i1).compareTo(ls.get(i2)))<br />
                            .get();<br />
      AbstractList&lt;T&gt; rest = (AbstractList&lt;T&gt;) ls.stream()<br />
                                                 .filter(e -> e != ls.get(minIdx))<br />
                                                 .collect(Collectors.toList());<br />
      AbstractList&lt;T&gt; sorted = new ArrayList&lt;&gt;();<br />
      sorted.add(ls.get(minIdx));<br />
      sorted.addAll(selectionSort(rest));<br />
      return sorted;<br />
    }<br />
  }</code></pre>
         </td>
         <td></td>
         <td>Madhav Nawani</td>
      </tr>
      <tr>
         <td>390</td>
         <td>The second-to-last sentence of Example 7.4 should end with, "...and lower-bounded by &Omega;(1)."</td>
         <td></td>
         <td></td>
      </tr>     
      <tr>
         <td>390</td>
         <td>The last sentence of Example 7.4 should read, "Therefore, by assuming those upper and lower bounds, we cannot conclude that binary search, in the average case, runs in &Theta;(lg n) time. Refining the upper and lower bounds to be tight allows us to correctly conclude that binary search runs in &Theta;(lg n) in the average case."</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>411</td>
         <td>Example 8.6, the second example in <code>testParse</code> should have <code>new NumNode)</code> written as <code>new NumNode(40)</code>. There should also be one closing parenthesis afterwards.</td>
         <td></td>
         <td></td>
      </tr>
      <tr>
         <td>420</td>
         <td>The distinction between concurrency and parallelism is poorly explained. The second sentence of the first paragraph of section 8.4 should say, "<i>Concurrency</i> describes '<i>juggled</i>' actions/computations, whereas <i>parallelism</i> refers to <i>simultaneous</i> actions/computations."</td>
         <td></td>
         <td></td>
      </tr>
   </tbody>
</table>








