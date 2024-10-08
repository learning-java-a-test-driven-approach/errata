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
        The <code>else if (b % 2 == 0)</code> case in the <code>powTRHelper</code> method should be:
        <pre><code>
        else if (b % 2 == 0) {
            return powTRHelper(n * n, b / 2, n * acc);
        }
        </code></pre>
      </td>
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
      <td>76</td>
      <td>Part (b) description should read: "Design the <code>isFactorionTR</code> tail recursive method, which solves the same problem as part (a), but uses tail recursion."</td>
      <td></td>
      <td>Owen Harris</td>
    </tr>
    <tr>
      <td>79</td>
      <td>Exercise 2.44 should include a clause saying that methods to make the problem trivial, e.g., <code>Integer.parseInt</code>, are disallowed.</td>
      <td></td>
      <td>Peter Perry</td>
    </tr>
    <tr>
      <td>136</td>
      <td>In Figure 3.9, the <code>add</code> method should instead say, "If <code>e</code> is not in <code>S</code>, it returns <code>true</code>; otherwise, it returns <code>false</code>."</td>
      <td></td>
      <td>Dylan Waintraub</td>
    </tr>
    <tr>
      <td>140</td>
      <td>In Figure 3.10, the <code>size</code> method should instead say that it returns the number of logical elements in the "map" rather than "set".</td>
      <td></td>
      <td>Dylan Waintraub</td>
    </tr>
    <tr>
      <td>148</td>
      <td>
        The code snippet of Example 3.40 should be as follows:
        <pre>
import java.util.ArrayDeque;
import java.util.Deque;
import java.util.Iterator;
import java.util.List;
import java.util.Stack;
          
class StackPrinter {
  public static void main(String[] args) {
    List<Integer> L = List.of(10, 20, 30, 40, 50);
    Stack<Integer> S = new Stack<>(List.of(10, 20, 30, 40, 50));
    for (int x : L) { S.push(x); }
    
    // Enhanced for loop prints the stack elements "incorrectly!"
    // An Iterator also has this issue.
    // We get "10, 20, 30, 40, 50" separated by newlines.
    for (int x : S) { System.out.println(x); }
    
    Deque<Integer> D = new ArrayDeque<>();
    for (int x : L) { D.push(x); }
    // An ArrayDeque corrects this problem.
    // We correctly get "50, 40, 30, 20, 10" separated by newlines.
    for (int x : D) { System.out.println(x); }
  }
}
      </pre>
      </td>
      <td></td>
      <td>Joshua Park</td>
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
        rows with data from the <code>&lt;header&gt;</code> column. An asterisk can be used to select all rows in the database."
      </td>
      <td></td>
      <td>Germinari</td>
    </tr>
    <tr>
      <td>367</td>
      <td>Remove type parameters: <code>IBinarySearch search = new TailRecursiveBinarySearch();</code>.</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>367</td>
      <td>The first two <code>assertEquals</code> semicolons should be changed to commas in the <code>assertAll(...)</code> block.</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>390</td>
      <td>The last sentence of Example 7.4 should read, "Therefore, concluding that, in the average case, binary search runs in &Theta;(lg n) time is incorrect."</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
