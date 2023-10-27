# Singly_linked_list
Basic Codes explaining concepts of linked lists

A. Basics - Basic code on singly-linked list Algorithm -

Create a class 'node' with data and a pointer to the next node.
Inside the 'node' class constructor, initialize data to 0 and next to NULL.
In the main function: a. Declare a pointer 'head' for the linked list. b. Create the first node, 'newnode1', set its data to 10, and assign it to 'head'. c. Create 'newnode2', 'newnode3', and 'newnode4' and set their data values. d. Link the nodes together by setting the 'next' pointers. e. Print the data, self-address, and next address for each node.
B. Access data by loop - Updated version of previous code with a loop used for displaying the elements. Algorithm - Algorithm for Creating a Singly Linked List and Displaying Its Properties:

Define a class named 'node' to represent a node in a singly linked list: a. Declare public member variables: 'data' (to store the node's data) and 'next' (a pointer to the next node). b. Create a constructor to initialize 'data' to 0 and 'next' to NULL.

In the 'main()' function: a. Declare a pointer variable 'head' to represent the head of the linked list.

Create several 'node' objects and set their 'data' values: a. Create 'newnode1' and set its 'data' to 10. b. Create 'newnode2' and set its 'data' to 20. c. Create 'newnode3' and set its 'data' to 30. d. Create 'newnode4' and set its 'data' to 40.

Link the nodes together to form a singly linked list: a. Set 'newnode1->next' to 'newnode2'. b. Set 'newnode2->next' to 'newnode3'. c. Set 'newnode3->next' to 'newnode4'.

Display the data, self-address, and next-address for each node: a. Print the 'data' value for each node. b. Print the self-address and next-address for each node.

Create a 'temp' pointer and initialize it to 'head'.

Use a 'while' loop to traverse the linked list: a. While 'temp' is not NULL: i. Print the 'data' value for the current node. ii. Print the self-address and next-address for the current node. iii. Update 'temp' to 'temp->next' to move to the next node.

End of the program.

C.Adder function - Uses functions to add elments at the nd of the list and display them. Algorithm - Algorithm for Creating and Displaying a Singly Linked List:

Define a class named 'node' to represent a node in a singly linked list: a. Declare public member variables: 'data' (to store the node's data) and 'next' (a pointer to the next node). b. Create a constructor to initialize 'data' to 0 and 'next' to NULL.

Declare a global pointer variable 'head' to represent the head of the linked list.

Create a function 'atBegining' to add a new node at the beginning of the list: a. Create a new node 'newnode'. b. Set 'data' in 'newnode' to the given 'data'. c. Set 'newnode->next' to the current 'head'. d. Update 'head' to point to 'newnode'.

Create a function 'end_adder' to add a new node at the end of the list: a. Traverse the list from the head to the last node. b. Create a new node 'newnode'. c. Set 'data' in 'newnode' to the given 'data'. d. Set the 'next' of the last node to 'newnode'.

Create a function 'display' to print the elements in the list: a. Initialize a pointer 'temp' to the 'head'. b. While 'temp' is not NULL, print the 'data' in the current node and move to the next node by updating 'temp' to 'temp->next'. c. Repeat the process until 'temp' becomes NULL.

In the 'main()' function: a. Create several 'node' objects and set their 'data' values. b. Link the nodes together to form a singly linked list. c. Call the 'end_adder' function to add more nodes to the end. d. Call the 'display' function to print the linked list.

End of the program.
