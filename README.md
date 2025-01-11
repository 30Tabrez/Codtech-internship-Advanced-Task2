# Codtech-internship-Advanced-Task2
# Singly Linked List Implementation Program

## Overview
This program implements a **Singly Linked List** in C, where users can perform operations like insertion, deletion, and traversal. A singly linked list is a linear data structure where each element (node) contains data and a reference (or link) to the next node in the list. This program demonstrates the creation of a singly linked list and supports the following operations:

- Insert at the beginning of the list
- Insert at the end of the list
- Insert at a specific position
- Delete from the beginning of the list
- Delete from the end of the list
- Delete a specific node
- Traverse and print the entire list

---

## Features
1. **Insertions**:
   - Insert a node at the **beginning** of the list.
   - Insert a node at the **end** of the list.
   - Insert a node at a **specific position** in the list.

2. **Deletions**:
   - Delete a node from the **beginning** of the list.
   - Delete a node from the **end** of the list.
   - Delete a **specific node** based on value.

3. **Traversal**:
   - Traverse the linked list and display all the nodes.

4. **Menu-Driven Interface**:
   - The program provides an interactive menu to perform different linked list operations.

---

## Instructions
1. **Menu Options**:
   The program displays a menu with the following choices:
   - **1. Insert at Beginning**: Inserts a node at the start of the list.
   - **2. Insert at End**: Inserts a node at the end of the list.
   - **3. Insert at Position**: Inserts a node at a specified position in the list.
   - **4. Delete from Beginning**: Removes the node from the start of the list.
   - **5. Delete from End**: Removes the node from the end of the list.
   - **6. Delete Specific Node**: Removes a node with a specific value.
   - **7. Traverse and Display List**: Displays all the nodes in the list.
   - **8. Exit**: Exits the program.

2. **Node Structure**:
   Each node contains two parts:
   - **Data**: The data stored in the node (in this case, an integer).
   - **Next**: A pointer to the next node in the list.

---

## How to Use
1. **Choose an Operation**:
   - After the program starts, you will be presented with a menu to choose the desired operation.
   - Enter the appropriate option and follow the prompts to perform the operation.

2. **Example Usage**:
   - To **insert a node at the beginning**, select option 1 and provide the value to be inserted.
   - To **delete a node from the beginning**, select option 4.
   - To **traverse the list**, select option 7.

---

## Compilation and Execution
1. Save the program code in a file named `linked_list.c`.
2. Open a terminal and compile the program:
   ```bash
   gcc linked_list.c -o linked_list
   ```
3. Run the program:
   ```bash
   ./linked_list
   ```

---

## Sample Screenshots

### **Main Menu**
The user is prompted with a menu to choose between different linked list operations.

![Main Menu Screenshot](https://via.placeholder.com/600x200.png?text=Main+Menu+Example)

### **Insert at Beginning**
Input Example:  
```
Enter the value to insert at the beginning: 5
```

Output:
```
Node inserted at the beginning. Linked list: 5 -> NULL
```

### **Insert at End**
Input Example:  
```
Enter the value to insert at the end: 10
```

Output:
```
Node inserted at the end. Linked list: 5 -> 10 -> NULL
```

### **Delete from Beginning**
Input Example:  
```
Deleting node from the beginning...
```

Output:
```
Node deleted from the beginning. Linked list: 10 -> NULL
```

### **Traverse List**
Input Example:  
```
Traversing the list...
```

Output:
```
Linked list: 5 -> 10 -> 15 -> NULL
```

---

## Code Walkthrough

1. **Main Program Flow**:
   - The program presents a menu where the user can select an operation.
   - The appropriate function is called based on the user's selection to insert, delete, or traverse the list.

2. **Linked List Functions**:
   - **Insertion Functions**:
     - `insertAtBeginning()`: Creates a new node and places it at the front of the list.
     - `insertAtEnd()`: Creates a new node and adds it to the end of the list.
     - `insertAtPosition()`: Inserts a node at a specific position in the list.
   
   - **Deletion Functions**:
     - `deleteFromBeginning()`: Removes the node at the beginning.
     - `deleteFromEnd()`: Removes the last node in the list.
     - `deleteSpecificNode()`: Deletes a node with a specified value.

   - **Traversal Function**:
     - `traverse()`: Traverses the list from the head to the end and prints the elements.

3. **Error Handling**:
   - The program checks for edge cases like attempting to delete from an empty list and handles them by displaying appropriate messages.
   - For insertions at invalid positions (e.g., out-of-bounds), the program will prompt the user to enter a valid position.

---

## Future Enhancements
1. **Doubly Linked List**: Extend the program to support doubly linked lists where nodes have pointers to both the next and previous nodes.
2. **Memory Management**: Add more advanced memory management techniques, such as handling memory leaks.
3. **Node Searching**: Add a function to search for a specific node by value and return the position.
4. **Error Handling**: Improve error handling for invalid operations, such as inserting at a position larger than the list size.

---

## License
This project is released under the MIT License.

---

## Contributions
Feel free to contribute by submitting pull requests, issues, or suggestions.

---

