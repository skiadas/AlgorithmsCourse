# Brute-Force algorithms

- Read 3.1, pages 97-101
    - What is the main idea behind the "brute force" approach?
    - The book lists at least four possible reasons why a brute-force solution to a problem might be desirable. What are they?
    - You can see visualizations of the various sorting algorithms on this site: [https://visualgo.net](https://visualgo.net). I strongly encourage you to play around with it, and visually see the three sorting algorithms we have seen so far (Counting, Selection, Bubble).
    - Study the **SelectionSort** algorithm.
        - What is the main idea of the SelectionSort algorithm?
        - Explain the use of the double-for loop, and in particular the indices for each loop.
        - What does the variable `min` represent in the loop? Be precise.
        - At intermediate steps of the algorithm, what part of the array, if any, is sorted?
        - Study Figure 3.1 which shows a run of the algorithm. What is the meaning of the vertical lines?
        - True or False: SelectionSort is an in-place sorting algorithm
        - True or False: SelectionSort is a stable sorting algorithm
        - What is the key operation in SelectionSort?
        - Analyze the time complexity of SelectionSort.
        - Is there a difference in SelectionSort between best-case and worst-case?
        - How many entry swaps are needed for SelectionSort?
            - Why might we care about this?
        - The pseudocode is presented assuming the list of numbers is stored as an array. Do you think the algorithm could work if the numbers were stored as a linked list? What would need to change?
        - Practice problems: 3.1.8, 3.1.10
    - Study the **BubbleSort** algorithm.
        - What is the main idea of BubbleSort? Why is it called that?
        - Explain the use of the double-for loop, and in particular the indices for each loop, especially the inner loop.
        - At intermediate steps of the algorithm, what part of the array, if any, is sorted?
        - Study Figure 3.2 which shows a run of the algorithm. What is the meaning of the vertical lines?
        - True or False: BubbleSort is an in-place sorting algorithm
        - True or False: BubbleSort is a stable sorting algorithm
        - Analyze the time complexity of BubbleSort.
        - Is there a difference in BubbleSort between best-case and worst-case?
        - How many entry swaps are needed for BubbleSort?
        - Practice problems: 3.1.11, 3.1.14