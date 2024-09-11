# Learning Java: A Test-Driven Approach (1e, 1st printing) Errata

Page vii: expose => exposure

Page 23: the `static double stats` method should return a `String`; not a `double`.

Page 26: on the fifth line, `if (x != 10 && y != 5) { y += 5; }` should instead be `if (x == 10 && y != 5) { y += 5; }`.

Page 41: the `else if (b % 2 == 0)` case in the `pow` method should be defined as

```Java
...
else if (b % 2 == 0) {
    return pow(n * n, b / 2);
}
...
```

Page 42: the `else if (b % 2 == 0)` case in the `powTRHelper` method should be defined as

```Java
...
else if (b % 2 == 0) {
    return powTRHelper(n * n, b / 2, n * acc);
}
...
```

Page 60, Example 2.16: the string `"gafia` should have an ending double quote: `"gafia"`

Page 76, Exercise 2.34: Part (b) should read, "Design the `isFactorionTR` tail recursive method, which solves the same problem as part (a), but uses tail recursion.", *found by Owen Harris.*

Page 367:
The `IBinarySearch<Integer> search = new TailRecursiveBinarySearch<>();` should not have the type parameters, because the method inside the class uses generic types directly. The fix is `IBinarySearch search = new TailRecursiveBinarySearch()`.

The `assertAll(...)` block has three `assertEquals` statements that end with semicolons. The first two should be changed to commas `,` or else the code fails to compile.
