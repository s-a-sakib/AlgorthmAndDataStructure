 **# Binary Segment Tree**

**A versatile data structure for efficient range queries and updates.**

## Overview

* **Stores information about intervals or segments of an array.**
* **Enables efficient queries over these segments, such as:**
    * Finding the sum, minimum, maximum, or other aggregate values within a range.
    * Identifying the first or last occurrence of a certain value within a range.
* **Supports updates to individual elements or entire ranges.**
* **Time complexity:**
    * Building the tree: O(n)
    * Queries: O(log n)
    * Updates: O(log n)

## Implementation

* **Implemented in (insert programming language)**
* **Key features:**
    * Clear and concise code with comments for readability.
    * Well-defined functions for building, querying, and updating the tree.
    * Test cases to ensure correctness.

## Usage

1. **Clone the repository:** `git clone [git@github.com:s-a-sakib/AlgorthmAndDataStructure.git](https://github.com/s-a-sakib/AlgorthmAndDataStructure.git)`
2. **Navigate to the project directory:** `cd SegmentTree`
3. **Build the project (if necessary):** `make`
4. **Run the examples:** `./examples`

## Examples

* **Finding the sum of elements in a range:**
```c++
int inputArray[] = {1, 3, 5, 7, 9, 11};
    int size = sizeof(inputArray) / sizeof(inputArray[0]);

    int *segmentTree = constructST(inputArray, size);

    cout << "Sum of values in given range = " << getSum(segmentTree, size, 1, 3) << endl;

```

* **Updating a value in the array:**
```c++
updateValue(inputArray, segmentTree, size, 1, 10);

    cout << "Updated sum of values in given range = " << getSum(segmentTree, size, 1, 3) << endl;
```

## Applications

* **Range sum queries in arrays.**
* **Range minimum/maximum queries.**
* **Finding the first/last occurrence of a value within a range.**
* **Range updates (e.g., adding a constant to all elements in a range).**
* **Geometric problems (e.g., finding intersections of line segments).**
* **Image processing (e.g., finding connected components).**

## Contributing

* **Fork the repository.**
* **Create a branch for your changes.**
* **Make your changes and commit them.**
* **Push your changes to your fork.**
* **Create a pull request.**

## License

* **MIT License**

**Feel free to explore, contribute, and utilize this implementation for your projects!**
