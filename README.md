**Student Record System**

**Description**: A simple Java application to manage student records using a linked list and stack.

**Features**:

1.Add Student Data

2.Display Student Data

3.Delete Student Data

4.Search Student

5.Update Student Data

6.Sort Student Data

7.Undo Last Action

 8.Exit Program

**Data Structures Used**:

1.Singly Linked List

2.Array based-Stack

3.Linear Search

4.Bubble Sort

## Time Complexity Analysis

The following table shows the expected time complexities for the main operations in this implementation:

|Operation|Time Complexity|Reason|
|---|---|---|
|Add Student|O(n)|The program traverses the list to reach the end.|
|Search Student|O(n)|Linear search may check every node.|
|Delete Student|O(n)|The program searches for the student before unlinking the node.|
|Display Students|O(n)|Every node is visited once.|
|Sort by GPA|O(n²)|In the worst case, Bubble Sort compares neighboring records over repeated passes.|
|Stack `push()`|O(1)|The new item is added at the top.|
|Stack `pop()`|O(1)|The top item is removed.|
|Stack `peek()`|O(1)|Only the top item is checked.|
|Stack `isEmpty()`|O(1)|The program checks whether `top == -1`.|

**Note:** Here, `n` is the number of student records.

**Group Members**: Faryal Ali ,Arooba ,Uzma Noureen ,Manahil Eman

**Course Code**: CS 216L

**Course**: Data Structures Lab

**Instructor**: Ma'am Rabia

**GitHub Repository Link**:

Manahil: [https://github.com/manahilx/Student_record_system](https://github.com/manahilx/Student_record_system)

Arooba: [https://github.com/Arooba19-cyber/My-Student-Record-System-is-2026.git](https://github.com/Arooba19-cyber/My-Student-Record-System-is-2026.git)

Faryal: [https://github.com/faryalali-12/CS2116L_Project-1_Group-1](https://github.com/faryalali-12/CS2116L_Project-1_Group-1)

Uzma: [https://github.com/uzma53/CS216L_Project1_Group1](https://github.com/uzma53/CS216L_Project1_Group1)
