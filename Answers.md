# Answers
- Try using a `TreeMap` and a `HashMap` instead of `MyHashMap`.
    - Are the resulting word frequencies any different?  
    The results when using `TreeMap` and `HashMap` are the same as when using `MyHashMap`.
    - Is the time performance any different? If so, how would you rank the three implementations 
    (in increasing order of time complexity)?  
    `HashMap` proves to be faster than `TreeMap`, though in comparison to `MyHashMap`, `HashMap` has the same time
    complexity for larger tables and a simpler complexity for smaller tables.
- How are % and Math.floorMod different? Which works more reliably for computing a hash table index?
- What is the time complexity of MyHashMap.size(), and how could you make it much more efficient?
- How does this implementation compare to one where you would directly use your linked Node class from the earlier 
assignment? Answer briefly in terms of ease of implementation, correctness, reliability, and performance.