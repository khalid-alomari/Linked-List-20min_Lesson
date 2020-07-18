## Doubly Linked List Starter Code
#### Don't worry; we will solve this in the `DoublyLinkedList` class together!
```python
# This is an input class. Do not edit.
class Node:
    def __init__(self, value):
        self.value = value
        self.prev = None
        self.next = None

# Hints:
# always make sure that to:
# store some of the nodes you are pointing at in temp variables 
# and keep track of orders that overriding some of these 
# pointers when implementing it! 

# Feel free to add new properties and methods to the class.
# Its easier to Start from the (containsNodeWithValue then remove) methods. 
# I highly recommend that you use a "helper method" for the remove method.
class DoublyLinkedList:
    def __init__(self):
        self.head = None
        self.tail = None

    def setHead(self, node):
        # Write your code here.
        pass

    def setTail(self, node):
        # Write your code here.
        pass

    def insertBefore(self, node, nodeToInsert):
        # Write your code here.
        pass

    def insertAfter(self, node, nodeToInsert):
        # Write your code here.
        pass

    def insertAtPosition(self, position, nodeToInsert):
        # Write your code here.
        pass

    def removeNodesWithValue(self, value):
        # Write your code here.
        pass

    def remove(self, node):
        # Write your code here.
        pass

    def containsNodeWithValue(self, value):
        # Write your code here.
        pass
```
