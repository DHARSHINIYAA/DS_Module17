# Ex22 Breadth First Graph
## DATE:21.04.2025
## AIM:
To write a printQueue C function of the given graph that is to be traversed in the breadth first manner.

![image](https://github.com/user-attachments/assets/f483f48c-6af0-4027-a993-01c108a50933)


## Algorithm
1. Start the program
2. Start from the front index of the queue.
3. If the queue is empty, print "Queue is empty".
4. Otherwise, print "Queue contains" and display all items from front to rear.
5. Return after printing the queue contents.
6. End the program

## Program:
```
/*
Program to traverse graph using BFS
#include<stdio.h>
#include<stdlib.h>
#define SIZE 40
struct queue{
int items[SIZE];
int front;
intrear;
};
struct queue* createQueue();
void enqueue(struct queue*q, int);
int dequeue(struct queue*q);
voiddisplay(struct queue*q);
int isEmpty(struct queue*q);
void printQueue(struct queue* q);
struct node{
int vertex;
struct node* next;
};
struct node*createNode(int);
struct Graph {
int numVertices;
struct node**adjLists;
int* visited;
};*/
void printQueue(struct queue*q){
int i=q->front;
if(isEmpty(q))
{
printf("Queue is empty");
}
else
{
printf("Queue contains ");
for(i=q->front;i<q->rear+1;i++)
{
printf("%d",q->items[i]);
}
}
}

Developed by: DHARSHINIYAA KS
RegisterNumber:  212223100004
*/
```

## Output:

![Screenshot 2025-05-12 204903](https://github.com/user-attachments/assets/e3487c4d-3990-4976-abc2-4281dc19bd6e)


## Result:
Thus, the code for the printQueue function of the following graph that is to be traversed in the breadth first manner is implemented successfully.
