AO2QO7
====
void reverse(struct node * head)
{
struct node *current=head, * prev=NULL, * next;
while(current)
{
next=current->next;
curent->next=prev;
current=next;
prev=current;
}
head=prev;
}
