# DFS/BFS
1. 0039	Combination Sum
2. 0040	Combination Sum II
3. 0046	Permutations
4. 0078	Subsets
5. 0079	Word Search
6. 0090	Subsets II
7. 0098	Validate Binary Search Tree
8. 0104	Maximum Depth of Binary Tree
9. 0112	Path Sum
10. 0113	Path Sum II   
  Remember to pop for backtrack. Need to practice a few more times.
11. 0129	Sum Root to Leaf Numbers
12. 0133	Clone Graph  
    Memorize BFS.  
14. 0199	Binary Tree Right Side View
15. 0200	Number of Islands
16. 0207	Course Schedule  
    Beware TC and SC
17. 0210	Course Schedule II
18. 0216	Combination Sum III  
    Beware TC and SC
19. 0429	N-ary Tree Level Order Traversal
20. 0337	House Robber III  
    Difficult. Memorize it. 
21. 0130	Surrounded Regions  
    Difficult. Memorize it
22. 0131	Palindrome Partitioning  
    Beware TC O(N * 2 ^ N), SC O(N)
23. 0491	Increasing Subsequences  
    Difficult. Memorize it.
24. 0513	Find Bottom Left Tree Value
25. 0127	Word Ladder
26. 0329	Longest Increasing Path in a Matrix  
    Difficult. Memorize it.
27. 0310	Minimum Height Trees    
    Difficult. Memorize it.
28. 0332	Reconstruct Itinerary  
    Extremely difficult. Memorize it 
29. 529	Minesweeper  
    A bit difficult as well.  
30. 0526	Beautiful Arrangement  
    Permuation. Save position instead of path as no need to find exact patj
31. 0430	Flatten a Multilevel Doubly Linked List  
  Modestly difficult. Memorize the code.  Should learn O(n) recursive one.  
32. 0419	Battleships in a Board
33. 0037	Sudoku Solver  
    Difficult. Memorize code. TC O(N! ^ N), SC O(N * N)
34. 0306	Additive Number  
    Backtrack. Understand code. 
35. 0093	Restore IP Addresses  
    TC O(N ^ 4)
36. 0576	Out of Boundary Paths
37. 0241	Different Ways to Add Parentheses  
    Each sub-expression can be split into two parts at each operator, generating a combination of left and right results which can be anywhere from 1 to Catalan(n) (which is an upper bound on the number of unique BSTs that can be formed with n nodes). The Catalan number grows approximately as 4^n / (n^(3/2) sqrt(pi)), which is less than 2^n.  
    
    Considering the above facts and the memoization, the upper bound on the time complexity is O(n * 2^n * n) = O(n^2 * 2^n) since for each operator we do two recursive calls and combine their results, plus the iteration for combining results that take O(n) time.
38. 0301	Remove Invalid Parentheses
39. 0126	Word Ladder II  
    BFS + DFS Backtrack
40. 0473	Matchsticks to Square  
     Backtrack  
    TC O(4 ^ N) because we have a total of N sticks and for each one of those matchsticks, we have 4 different possibilities for the subsets they might belong to or the side of the square they might be a part of.
41. 0417	Pacific Atlantic Water Flow  
    Typical DFS. In DFS, have parameter previous height, visited and result that represent whether water can fill to occean.  
