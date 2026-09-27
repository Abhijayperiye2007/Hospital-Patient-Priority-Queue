# Hospital Patient Priority Queue - Max Heap, Heap Sort and Quick Sort

## Input
45 72 30 90 65 50 85

## Files
- `patient_priority_assignment.c` - C source code implementing max-heap insertion, heap sort and quick sort.
- `input.txt` - given input data.
- `output.txt` - execution output.
- `trace_table.txt` - important intermediate trace tables.
- `comparison.txt` - complexity and performance comparison.

## Algorithms
1. Max Heap insertion: higher severity = higher priority.
2. Heap Sort: in-place sorting using a max heap.
3. Quick Sort: Lomuto partition with the last element as pivot.

## Final conclusion
For a hospital that continuously inserts patients and needs the highest-priority patient immediately, a Max Heap priority queue is the appropriate data structure. Insertion is O(log n), highest-priority access is O(1), and deletion of the highest-priority patient is O(log n). Heap Sort and Quick Sort are sorting algorithms and require processing the collection rather than maintaining an immediately accessible priority structure.
