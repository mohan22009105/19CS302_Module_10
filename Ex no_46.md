# EX 46 C function to traverse the linked list and display it in the following format.

## AIM:
To write a C function to traverse the linked list and display it in the following format.

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
```

## Output:

<img width="1101" height="521" alt="image" src="https://github.com/user-attachments/assets/acb03f6f-8cf6-4865-b6e2-b4060a709825" />




## Result:
Thus the program was executed and the output was verified successfully.
