# Ex7 Priority Queue
## DATE:
## AIM:
To formulate the C code to display the elements of the priority queue after insertion and deletion operation.

## Algorithm
1. Read number of elements `m` to insert, then insert each element into the heap using `insert()`.
2. Read number of elements `m` to delete, then delete each specified element using `deleteRoot()`.
3. Use helper functions `insert()` and `deleteRoot()` to maintain the Max-Heap property.
4. After all insertions and deletions, print the final heap using `printArray()`.
5. The array represents a Max-Heap, where each parent node is greater than or equal to its children.  

## Program:
```
/*
Program to o display the elements of the priority queue after insertion and deletion operation
Developed by: T.RUCHITRA
RegisterNumber: 212223110043
/*#include <stdio.h>
int size = 0;
*/
int main() {
    int m,k,e,r;
  int array[10];
  //m is the number of elements to be inserted/deleted,k is the array index,e is the element to be inserted and r is the element to be deleted
  //type your code here...
  scanf("%d",&m);
  for(k=0;k<m;k++){
      scanf("%d",&e);
      insert(array,e);
      
  }
  scanf("%d",&m);
  for(k=0;k<m;k++){
      scanf("%d",&r);
      deleteRoot(array,r);
  }
  printf("Max-Heap array after insertion and deletion: ");
  printArray(array,size);
  
}
*/
```

## Output:
![prique](https://github.com/user-attachments/assets/d49f2e99-46f6-4d98-95fa-54aa0294f0e0)

## Result:
Thus, the C program to display the elements of the priority queue after insertion and deletion operation is implemented successfully
