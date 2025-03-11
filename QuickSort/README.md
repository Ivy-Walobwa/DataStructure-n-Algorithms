# QuickSort

A divide-and-conquer sorting algorithm that recursively partitions a list into smaller sublists based on a chosen pivot.

- **Input** - Unsorted list of elements
- **Output** - Sorted list of elements

## Algorithm

1. Select a **pivot** element from the list.
2. Partition the list into two sublists:
   - Elements smaller than the pivot.
   - Elements greater than or equal to the pivot.
3. Recursively apply QuickSort to the sublists.
4. Combine the sorted sublists and pivot to form the final sorted list.

**Time Complexity**:

- Best/Average Case: O($n \log n$)
- Worst Case (when the pivot is poorly chosen): O($n^2$)
