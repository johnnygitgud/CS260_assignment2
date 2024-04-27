# CS260_assignment2

 First create a queue structure with these functions:

    add: Put an item at the end of the queue
    remove: Take out and give back the item from the front of the queue
    isEmpty: Check if the queue has no items
    isFull: Check if the queue has reached its maximum capacity

To make the queue work, we'll track:

    Where the front and back of the queue are
    How many items are in the queue

For a list structure that allows adding and removing items at any position, we'll use these functions:

    add: Inserts an item at a specific spot in the list
    remove: Erases the item from a specific spot in the list
    isEmpty: Checks if the list doesn't have any items
    size: Tells us how many items are in the list

To ensure the list works, we'll need:

    A pointer to the beginning of the list
    The count of items in the list
    The position of each item in the list
