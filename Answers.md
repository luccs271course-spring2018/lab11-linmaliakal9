# Answers
- Try using a `TreeMap` and a `HashMap` instead of `MyHashMap`.
    - Are the resulting word frequencies any different?  
    The results when using `TreeMap` and `HashMap` are the same as when using `MyHashMap`.
    - Is the time performance any different? If so, how would you rank the three implementations 
    (in increasing order of time complexity)?  
    `HashMap` proves to be faster than `TreeMap`, though in comparison to `MyHashMap`, `HashMap` has the same time
    complexity for larger tables and a simpler complexity for smaller tables.  
    The ranking would be: 1. `HashMap` 2. `MyHashMap` 3. `TreeMap`
- How are `%` and `Math.floorMod` different? Which works more reliably for computing a hash table index?  
The `%` operator is use to calculate and give the remainder of two numbers being divided. `Math.floorMod` is different
because it considers negative numbers and calculates the integer less than or equal to the quotient. When the signs
of the two numbers being divided are not always positive, the `%` operator would give a different answer than 
`Math.floorMod`. Therefore, `Math.floorMod` is more reliable when computing a hash table intex in case of a 
negative result. 
- What is the time complexity of `MyHashMap.size()`, and how could you make it much more efficient?  
The time complexity of it is O(n). In order to make it more efficient, one could increase the size for every new
item added. 
- How does this implementation compare to one where you would directly use your linked Node class from the earlier 
assignment? Answer briefly in terms of ease of implementation, correctness, reliability, and performance.  
The implementations of the two produce the same outcome and are done correctly. `MyHashMap` seems to be more
reliable in what you can do with it and faster in its performance than using the linked Node class.