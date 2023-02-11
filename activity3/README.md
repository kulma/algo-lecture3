# Activities

## Task 1:

- Refer to the following link. Discuss how Queues based on linked lists works:
  https://www.cs.usfca.edu/~galles/visualization/QueueLL.html

  > 

## Task 2:

- The following snippet is from `./src/queue.cpp` lines 8-10. What happens if `front`, `rear` and `temp` were not global variables?
> The code won't execute?

```cpp
struct node *front = NULL;
struct node *rear = NULL;
struct node *temp;
```

## Task 3:

- The following snippet is from `./src/queue.cpp` lines 11-28. Discuss in groups how the code works:

```cpp
void Insert(int val)
{
    if (rear == NULL) // execute this code if rear is empty
    {
        rear = new node; //create a new node rear
        rear->next = NULL; // assign null to rear-next
        rear->data = val; // assign int val to rear-data
        front = rear; // assign rear to front
    }
    else //else
    {
        temp = new node; // create a new node temp
        rear->next = temp; // assign temp to rear-next
        temp->data = val; // assign int val to temp-data
        temp->next = NULL; // assign null to temp-next
        rear = temp; // assign temp to rear
    }
}
```

## Task 4: Individual, at home

- Discuss the various operations that can be performed on a linked list. Refer to the following link:
  https://www.softwaretestinghelp.com/linked-list/

> Operations for linked list are insertion (three different ways) and deletion 

## Links

- https://cpp.sh/
