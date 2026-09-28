# CMPS 2200 Recitation 05
## Answers

**Name:**_Srikanya Balaji Garuda________________________
**Name:**_________________________


Place all written answers from `recitation-05.md` here for easier grading.




- **3) (2 pts)** What is the work and span of `get_positions`? (assume our more efficient version of `scan` from class)

Work = O(n) (still n computations)
Span = O(log n) using the efficient span because of parallelization, but span can also be considered O(n) by my written function because the concatentation isn't parallelized

- **5) (2 pts)** What is the work and span of `construct_output`?
Work = O(n) 
Span = O(n)


- **6) (2 pts)** What is the work and span of `supersort`?
Work = O(n + k); k being max
Span = O(n + k); k being max


- **8) (2 pts)** What is work and span of `count_values_mr`?
Work = O(n^2 + k); flatten with plus function
Span = O(nlog n + k); nlogn from sorting the pairs
