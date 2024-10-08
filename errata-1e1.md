| Page  | Error/Correction                                                                                                                                                                | Notes | Credits         |
|-------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|-----------------|
| vii   | Replace "expose" with "exposure".                                                                                                                                                |       |                 |
| 23    | The `static double stats` method should return a `String`, not a `double`.                                                                                                       |       | Marlena Ames     |
| 26    | Condition `if (x != 10 && y != 5) { y += 5; }` should be `if (x == 10 && y != 5) { y += 5; }`.                                                                                   |       | Ty Rimedio       |
| 41    | The `else if (b % 2 == 0)` case in the `pow` method should be: <pre><code>else if (b % 2 == 0) { return pow(n * n, b / 2); }</code></pre>                                         |       |                 |
| 42    | The `else if (b % 2 == 0)` case in the `powTRHelper` method should be: <pre><code>else if (b % 2 == 0) { return powTRHelper(n * n, b / 2, n * acc); }</code></pre>               |       |                 |
| 60    | Add the missing ending double quote: `"gafia"`.                                                                                                                                  |       |                 |
| 76    | Part (b) description should read: "Design the `isFactorionTR` tail recursive method, which solves the same problem as part (a), but uses tail recursion."                        |       | Owen Harris      |
| 79    | Exercise 2.44 should include a clause saying that methods to make the problem trivial, e.g., `Integer.parseInt`, are disallowed.                                                  |       | Peter Perry      |
| 136   | In Figure 3.9, the `add` method should instead say, "If `e` is not in `S`, it returns `true`; otherwise, it returns `false`."                                                     |       | Dylan Waintraub  |
| 140   | In Figure 3.10, the `size` method should instead say that it returns the number of logical elements in the "map" rather than "set".                                               |       | Dylan Waintraub  |
| 148   | <pre><code>
import ... class ... { }

</code></pre>                                                                                                                                  |       | Joshua Park      |
| 176   | The third example in Exercise 3.24 should have the 11 changed to a 1. The description should also change 1 + 4 + 4 = 9 to 4 + 1 + 4 = 9.                                          |       | Josh Rudnik      |
| 185   | Exercise 3.65 should say, "In particular, we have a 2D array of strings whose first row contains column headers to a database. Examples of such columns may be 'ID', 'Name', 'Age'|       | Germinari        |
|       | , 'Salary', and so forth." The last sentence of the first paragraph should be removed as there is no context. In the second paragraph, change the last few words to "...returns   |       |                 |
|       | the data from the rows that satisfy the criteria enforced by the command." Change the definition of a `Command` to `A Command is "SELECT <count> <header> WHERE <predicate>"`.    |       |                 |
|       | Update the third paragraph to say "The `SELECT` command receives a `<count>` and a `<header>` to designate that the command should return *n* rows with data from the `<header>`. |       |                 |
| 367   | Remove type parameters: `IBinarySearch search = new TailRecursiveBinarySearch();`.                                                                                               |       |                 |
| 367   | The first two `assertEquals` semicolons should be changed to commas in the `assertAll(...)` block.                                                                               |       |                 |
| 390   | The last sentence of Example 7.4 should read, "Therefore, concluding that, in the average case, binary search runs in Θ(lg n) time is incorrect."                                 |       |                 |
