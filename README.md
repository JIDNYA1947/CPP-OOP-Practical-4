# C++ OOP Practical: Pointers, References & Dynamic Memory

## Aim

1. Implement pointers and references using a real-life student marks example.
2. Implement dynamic memory allocation and deallocation using `new[]` and `delete[]` with student marks data.

## Programs

### Program A — Pointers and References

File: `Pointers and References.cpp`

Real-life context: a student's marks are updated using a pointer and a reference.

* A pointer is used to update the marks.
* A reference is used to update the marks.
* The address of the marks is displayed.

### Program B — Dynamic Memory

File: `Dynamic memeory using new and delete operators.cpp`

Real-life context: a variable number of students can have different marks. The program dynamically allocates an array of student marks using `new[]`, calculates the total and average.

## Sample Output

### Program A

```text
Enter student marks: 65

Marks before using pointer and reference = 65
Address of marks = 0x...
Address stored in pointer = 0x...
Marks after using pointer = 78
Marks after using reference = 85
```

### Program B

```text
Enter number of students: 3
Enter marks of 3 students:
Student 1: 75
Student 2: 80
Student 3: 85

Total Marks: 240
Average Marks: 80
Dynamic memory released successfully.
```



## Concepts Demonstrated

* Pointer declaration and dereferencing
* Address-of operator `&`
* Reference declaration
* Updating marks using pointer
* Updating marks using reference
* Runtime allocation using `new[]`
* Dynamic array
* `for` loop
* Calculating total marks
* Calculating average marks
* Memory release using `delete[]`
* Setting a pointer to `nullptr` after deletion

