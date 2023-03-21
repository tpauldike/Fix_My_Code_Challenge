# Fix-My-Code Challenge
A challenge that put to test my ability to **debug** programs written in `python`, `javascript`, `ruby` and `c` programming languages.
## Mandatory Tasks
### [Fizzbuzz](./0-fizzbuzz.py)
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
 Well, you may compared my code and this to see what I figured out was the problem

### [Print Square](./1-print_square.js)
