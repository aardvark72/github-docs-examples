# Writing Good Documentation

## Step 1 - Using Codeblocks
Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks(`)
- Not to be confused with quotations(')
- When you can you should attempt to apply syntax highlighting to your codeblocks

  

```python
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

![download](https://github.com/aardvark72/github-docs-examples/assets/125646400/c5dd0bfe-6ba0-41e4-8a93-9dbdcf8aab07)

Good Cloud Engineers use codeblocks for both code and Erros that appear in the console.


```bash
# This code will raise a ZeroDivisionError
try:
    result = 5 / 0
except ZeroDivisionError as e:
    print(f"Error: {e}")
```

> Here is an example of using a codeblock for an erros that appears in bash.


## Step 3 - Use Github Flavoured Markdown  Task Lists

Github extends Markdown to have a list where you can check off items

- [x] Finish Step1
- [] Finish Step2
- [x] Finish Step3


## Step 4 - use Emojis(optional)

Github Flavored Markdwon (GFM) supports emoji shortcodes

|Name|Shortcode|Emoji|
|---| --- | ---| 
| Cloud | `:cloud:`| :cloud: |





## References

- [Github Flavoured Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Github emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

