# Activities

## Task 1

- Refer to the following link. Discuss how bubble sort works:
  https://opendsa-server.cs.vt.edu/embed/bubblesortAV

> Bubble sort uses two for-loops to iterate through the adjacent elements of the array. At the end of the outer loop, the largest element in the array is bubbled up to the end of the array.


## Task 2

- Refer to the following link. Your task is to show the behavior for one iteration of the outer for loop of Bubble Sort (Try at least 3 cases).
  https://opendsa-server.cs.vt.edu/ODSA/Exercises/Sorting/BubsortPRO.html

> OK


## Task 3

- The following snippet is from `./src/bubble.cpp` lines 16-28. Discuss in groups how the code works:

```cpp

    for (i = 0; i < 10; i++) // for loop that we continue as long as i is smaller than 10
    {
        for (j = i + 1; j < 10; j++) // for loop that we continue as long as j is smaller than 10
        {
            if (a[j] < a[i]) // check if j is smaller than i
            {
                temp = a[i]; // put i in temp
                a[i] = a[j]; // put j in i
                a[j] = temp; // put temp in j
            }
        }
        pass++; // increase variable named pass
    }
```

- The following snippet is from `./src/selection.cpp` lines 34-41. Discuss in groups how the code works:

```cpp
    for (j = i + 1; j < 10; j++) // for loop that we continue as long as j is smaller than 10
    {
        if (myarray[j] < ele_small) // check if ele_small is smaller than myarray[j]
        {
            ele_small = myarray[j]; //put myarray[j] to ele_small
            position = j; // put j to position
        }
    }
```

## Task 4: Individual, at home

- Discuss the complexity analysis of selection sort. Refer to the link below:
  https://www.softwaretestinghelp.com/selection-sort/

## Links

- https://cpp.sh/
