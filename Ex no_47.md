# EX 47 C function to insert a node in a linked list.
## DATE:17/3/26
## AIM:
To write a C function to insert a node in a linked list.

## Algorithm
Start.
Define a variables.
Write a function to insert a node in a linked list.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End

## Program:
```
/*
C function to insert a node in a linked list.

struct Node{ 
char data; 
struct Node *next; 
}*head; 
 
 
void insert(char data) 
{ 
struct Node *n=(struct Node*)malloc(sizeof(struct Node)); 
struct Node*temp; 
if(head==NULL) 
{ 
head=n; 
n->data=data; 
n->next=NULL; 
temp=head; 
return; 
} 
 
}  
else 
{ 
while(temp->next!=NULL) 
{ 
temp=temp->next; 
} 
n->next=NULL; 
n->data=data; 
temp->next=n; 
} 
}
*/
```

## Output:

<img width="530" height="669" alt="image" src="https://github.com/user-attachments/assets/055a3939-2d54-4bfd-ae90-2d9a7d79ef35" />


## Result:
Thus the program was executed and the output was verified successfully.
