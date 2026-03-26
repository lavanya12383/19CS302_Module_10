# EX 49 C function to search an element in the doubly linked list.
## DATE:17/3/26
## AIM:
To write a C function to search an element in the doubly linked list.

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
C function to search an element in the doubly linked list.

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
 
 SAVEETHA ENGINEERING COLLEGE  
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
*/
```

## Output:


<img width="670" height="595" alt="image" src="https://github.com/user-attachments/assets/317817ee-744f-40b0-be6e-9be00c1c61cc" />

## Result:
Thus the program was executed and the output was verified successfully.
