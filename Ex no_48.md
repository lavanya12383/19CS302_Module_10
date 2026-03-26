# EX 48 C functions to perform all basic operations in Doubly Linked List.
## DATE:17/3/26
## AIM:
To write a C functions to perform all basic operations in Doubly Linked List.

## Algorithm
Start.
Define a variables.
Write a function to search an element in the double linked list..
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End  

## Program:
```
/*
C functions to perform all basic operations in Doubly Linked List.

struct Node 
{ 
struct Node *prev; 
struct Node *next; 
int data; 
}*head; 
 
void search(int data) 
{ 
struct Node *temp; 
int item=data,i=0,flag; 
temp=head; 
if(temp==NULL) 
{ 
printf("Empty list\n"); 
} 
else{ 
while(temp!=NULL) 
{ 
if(temp->data == item) 
{ 
printf("item %d found at location %d",item,i+1); 
flag=0; 
} 
i++; 
temp=temp->next; 
} 
if(flag!=0) 
{ 
printf("Item not found\n"); 
} 
} 
} 
*/
```

## Output:


<img width="928" height="820" alt="image" src="https://github.com/user-attachments/assets/0ba1e5e9-42cb-4158-8b1a-0824bbe32ef7" />

## Result:
Thus the program was executed and the output was verified successfully.
