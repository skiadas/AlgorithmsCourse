# Decrease-by-one algorithms: Insertion Sort

- Read 4.1, pages 131-138
    - Describe how in general the "decrease-by-one" and "decrease-by-constant-factor" algorithms work.
    - Describe the main approach to sorting that the **Insertion Sort** algorithm takes. How is this an illustration of the "decrease-by-one" approach?
    - Study the algorithm for InsertionSort.
        - What is the meaning of the index $i$? Why does it start from 1?
        - What is the meaning of the index $j$?
        - Explain the condition in the `while` loop. Why is that the right test?
        - What is the meaning of the assignment `A[j+1] <- A[j]`?
        - Why do we need the variable `v`?
    - At intermediate parts of the InsertionSort algorithm, what part of the array, if any, is sorted?
        - Are those values in their final locations?
        - How does that compare with SelectionSort and BubbleSort?
    - Analyze the worst-case and best-case efficiency of InsertionSort. When does the best base occur?
    - Practice problems: 4.1.7, 4.1.8, 4.1.9
    - Challenge: 4.1.11, 4.1.12
