# Ex23 Depth First Graph
## DATE:24.4.2025
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1. Start the program
2. Allocate memory for a new node.
3. Set the vertex field of the new node to the given value v.
4. Set the next pointer of the new node to NULL.
5. Return the newly created node.
6. End the program.

## Program:
```
/*
Program to traverse the graph below in the depth first fashion
#include<stdio.h>
#include<stdlib.h>
struct node{
int vertex;
struct node* next;
};
struct node*createNode(int v);
struct Graph {
int numVertices;
int* visited;
//We need int**to storeatwo dimensionalarray.
//Similary, weneedstruct node**tostoreanarrayofLinked lists
struct node** adjLists;
};*/
struct node*createNode(int v) {
struct node* newNode=malloc(sizeof(struct node));
newNode->vertex=v;
newNode->next=NULL;
return newNode;
}

Developed by: DHARSHINIYAA KS
RegisterNumber:  212223100004
*/
```

## Output:

![image](https://github.com/user-attachments/assets/57fe010c-0acf-4ddf-b090-cb059a50269d)


## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
