# EX 48 C functions to perform all basic operations in Doubly Linked List.

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
```

## Output:

<img width="990" height="870" alt="image" src="https://github.com/user-attachments/assets/7c516f96-aebd-45a7-acdd-3c2113433ee3" />



## Result:
Thus the program was executed and the output was verified successfully.
