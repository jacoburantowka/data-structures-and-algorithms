# Linked List

A **Linked List** is a linear collection of data elements, in which liner order is not given by their physical placement in memory. Instead, each element _points_ to the next.

It is a data structure consisting of a group of nodes which together represent a sequence. In its most basic form, each node is composed of data and a reference (in other words - a link) to the next node in the sequence. The last node is linked to a terminator used to signify the end of the list.

This structure allows for efficient insertion or removal of elements from any position in the sequence during iteration. More complex variants add additional links, allowing efficient insertion or removal from arbitrary element references. A drawback of linked lists is that access time is linear. Faster access, such as random access is not feasible. Arrays have better cache locality as compared to linked lists.

## Complexities

### Time Complexity

| Access | Search | Insertion | Deletion |
|--------|--------|-----------|----------|
| O(n)   | O(n)   | O(1)      | O(n)     |

### Space Complexity
O(n)
