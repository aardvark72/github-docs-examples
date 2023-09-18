# github-docs-examples

## Step 1 - Using Codeblocks
Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create coedblocks in markdown you need to use three backticks(`)
- Not to be confused with quotations(')
- When you can you should attempt to apply syntax highlighting to your codeblocks

  

``` ipython
function generateFibonacci(n) {
  let fibonacciSeries = [];
  let a = 0;
  let b = 1;

  for (let i = 0; i < n; i++) {
    fibonacciSeries.push(a);
    let temp = a;
    a = b;
    b = temp + b;
  }

  return fibonacciSeries;
}

const n = 10; // You can change 'n' to generate a different number of Fibonacci numbers
const fibonacciNumbers = generateFibonacci(n);
console.log(fibonacciNumbers);
```
