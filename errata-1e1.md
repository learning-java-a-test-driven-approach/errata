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
      <td>The <code>else if (b % 2 == 0)</code> case in the <code>pow</code> method should be:
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
      <td>The <code>else if (b % 2 == 0)</code> case in the <code>powTRHelper</code> method should be:
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
    <tr>
      <td>392</td>
      <td>The first sentence should read, "The problem here is that, there is a point at which picking a constant c will not satisfy the inequality for all n greater than n0."</td>
      <td></td>
      <td></td>
    </tr>    
  </tbody>
</table>
