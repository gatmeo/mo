## Storyboard: Combinatorics

### Introduction to nPr
- Definition: arranging n distinct objects in a particular order.
- Derivation of nPr formula using example of 3P2:
    - Consider an example where n = 3 and we want to arrange 2 objects.
    - List all possible arrangements: AB, AC, BA, BC, CA, CB.
    - Formula for nPr: nPr = n! / (n-r)!.

### Introduction to nCr
- Definition: choosing r objects out of n without regard to order.
- Observation that 2! permutations merge to 1 in nCr.
- Derivation of nCr formula: nCr = nPr / r!.

### Introduction to sets and functions
- Explanation of sets and functions between sets.
- Map between nPr and nCr can be rephrased as a map between sets.
- Number of elements in set of all combinations: nCr.
- Formula for nPr and nCr: nPr = r! * nCr.
- Map between n! and nPr: n! = nPr * (n-r)!.

### Finding number of permutations on identical elements
- Example problem: finding number of ways to arrange AABCD, or AAABBBBCC in general.
- Construct two solutions: 
    - One using the idea of functions Perm(A_1A_2BCD) -> Perm(AABCD).
    - The other using only nCr.

### Introduction to nHr
- Definition: distributing r identical candies to n students (with the possibility of some students receiving no candies).
- Use the situation of 2 identical candies to 5 students as an example.
- Explain that we can split it into cases, then ask about what's the general solution.

### Introduction to balls and sticks
- Introduce the concept of balls and sticks.
- Imagine n identical balls and r-1 identical sticks.
- The sticks divide the balls into r groups.

### Deriving the general formula for nHr
- Explain how each balls and sticks configuration maps bijectively to a situation of candies distribution.
- Derive the general formula for nHr: nHr = (n+r-1) choose (r-1).

### Conclusion
- Recap of the concepts covered (nPr, nCr, nHr, balls and sticks).
- Summary of the formulas for nPr, nCr, and nHr.
- Mention that combinatorics is a fundamental concept in mathematics and is used in many fields.
