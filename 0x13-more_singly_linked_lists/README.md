#Contans -print_listint.c

#Task 2
Write a function that adds a new node at the beginning of a listint_t list.

    Prototype: listint_t *add_nodeint(listint_t **head, const int n);
    Return: the address of the new element, or NULL if it failed

#Task 3
Write a function that adds a new node at the end of a listint_t list.

    Prototype: listint_t *add_nodeint_end(listint_t **head, const int n);
    Return: the address of the new element, or NULL if it failed
#Task 4
Write a function that frees a listint_t list.

    Prototype: void free_listint(listint_t *head);

#Task 5
Write a function that frees a listint_t list.

    Prototype: void free_listint2(listint_t **head);
    The function sets the head to NULL

#Task 6
Write a function that deletes the head node of a listint_t linked list, and returns the head node’s data (n).

    Prototype: int pop_listint(listint_t **head);
    if the linked list is empty return 0

#Task 7
Write a function that returns the nth node of a listint_t linked list.

    Prototype: listint_t *get_nodeint_at_index(listint_t *head, unsigned int index);
    where index is the index of the node, starting at 0
    if the node does not exist, return NULL
