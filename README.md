# linked-link-in-c-plus-plus # Aim: To study and implement Linked List

# Software used: VS Code

# Theory: 

•	Linked List is a linear data structure, in which elements are not stored at a contiguous location, rather they are linked using pointers. 

•	Linked List forms a series of connected nodes, where each node stores the data and the address of the next node.

 Why linked list data structure needed?
 
•	Dynamic Data structure: The size of memory can be allocated or de-allocated at run time based on the operation insertion or deletion.

•	Ease of Insertion/Deletion: The insertion and deletion of elements are simpler than arrays since no elements need to be shifted after insertion and deletion, Just the address needed to be updated.

•	Efficient Memory Utilization: As we know Linked List is a dynamic data structure the size increases or decreases as per the requirement so this avoids the wastage of memory. 

•	Implementation: Various advanced data structures can be implemented using a linked list like a stack, queue, graph, hash maps, etc.

 # Algorithm:

 Program 1:

 1.Start
 
 2.Define a class named Node with:
 
 3. An integer data member val to store the node's value.
    
4.A pointer next of type Node* to point to the next node.

5.Create a constructor for the class Node that:

6.Takes an integer input data.

7.Initializes val with data.

8.Sets next to NULL.

9.In the main function:

10.Create a new node dynamically using new Node(1) with value 1.

11.Print the value stored in the node (val).

12.Print the next pointer (which should be NULL).

13.End

Program 2:

1.Start

2.Define a class Node with:
Integer data to store node value.
Pointer next to the next node.

3.Create a constructor for Node to initialize data and set next to NULL.

4.Define insert_head function:
Create a new node with given data.
Set the new node’s next to the current head.
Update head to point to the new node.

5.Define display function:
Start from head.
Traverse each node until NULL.
Print the node’s data followed by ->.
At the end, print NULL.

6.In main:
Initialize head to NULL.
Insert nodes with values 1, 2, and 3 at head.
After each insertion, call display to show the list.

7.End

Program 3:

1.Define a Node Structure

Create a class Node with:

An integer val to store data.

A pointer next to the next node.

Define a constructor to initialize val and set next to NULL.

2.Create Nodes

Create three nodes:

n1 with value 10

n2 with value 20

n3 with value 30

3.Link the Nodes

Set n1->next to n2

Set n2->next to n3

Now the list is: n1 → n2 → n3 → NULL

4.Traverse the List

Initialize a pointer temp to point to n1 (head of the list).

While temp is not NULL:

Print temp->val

Move temp to temp->next

5.End Program

Return 0 to indicate successful execution.

# CONCLUSION: 

hence we have studied and learnt to implement linked list in c ++.
