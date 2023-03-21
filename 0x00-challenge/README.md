# Fix-My-Code Challenge
A challenge that put to test my ability to **debug** programs written in `python`, `javascript`, `ruby` and `c` programming languages.
## Mandatory Tasks
### 0. [Fizzbuzz](./0-fizzbuzz.py)
This task required that I debug an implementation of the fizzbuzz program in `python` that never printed `FizzBuzz` but printed only `Fizz` and `Bizz`.
This is what this segment of the original looked liked:
```python
    tmp_result = [] 
     for i in range(1, n + 1): 
         if (i % 3) == 0: 
             tmp_result.append("Fizz") 
         elif (i % 3) == 0 and (i % 5) == 0: 
             tmp_result.append("FizzBuzz") 
         elif (i % 5) == 0: 
             tmp_result.append("Buzz") 
         else: 
             tmp_result.append(str(i)) 
     print(" ".join(tmp_result))
 ```
 Well, you may compare my code to what is displayed here, to see what I figured out was the problem

### 1. [Print Square](./1-print_square.js)
This `javascript` program is supposed to print a square with the character `#` whose size is the number passed to it on the command line (as an argument) when running it, but it had some bug in this particular line of code:
```js
size = parseInt(process.argv[2], 16)
```
The above line of code made the program to print a square of size 15 rather than 10, when 10 was passed as the argument.
Compare this to what I have in my code to see what I changed; if you know what hexadecimals are, read a little about `parseInt` in `javascript` to understand what really happened there.

### *. [Real Square](./real_square.js)
This was just me playing with [1-print_square.js](./1-print_square.js) to have the square really appear like a square.
I used `console.error()` instead of `process.stderr.write()` and `console.log()` instead of `process.stdout.write()`.
The result when the program is ran, made the name *print square* to make more sense.
