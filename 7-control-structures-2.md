# Control Structures Part 2

Fundamentally, computers do the same tasks over and over again. Such behavior is often referred to as iterating, or looping.

The _loop_ control structure allows us to repeat actions in certain contexts. 

Consider the following statements:

1. Check if it is raining.
2. If it is raining, wear a raincoat.
3. Wear a raincoat.
   
What if we wish to perform this series of actions more than once? After all, if it is not raining now, it may yet rain in the future. We can accomplish this type of behavior with a loop (of which there are a variety but each remains similar in spirit).

```
while is_raining:
    
    is_raining = ?

    if is_raining:
        print("Wear a raincoat")
```

The above pseudo-code snippet uses a question mark to elide how we check to see if it is raining. This will be introduced in future sessions, but is immaterial to the concept at hand. The program will continue to print the phrase _Wear a raincoat_ as long as the datum **is_raining** remains true.


