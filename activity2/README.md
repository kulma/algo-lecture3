# Activities

## Task 1

- Refer to the following link. Discuss how bubble Insertion works:
  https://opendsa-server.cs.vt.edu/ODSA/AV/Sorting/insertionsortAV.html

  > Compare the second element to first and swap if second is smaller than first. Compare third element to second and first, swap if necessary. Compare next one to all its previous elements and so on...

## Task 2

- The following snippet is from `./src/insertion.cpp` lines 12-22. Discuss in groups how the code works:

```cpp
    for (int k = 1; k < 10; k++) //For-loop as long as k is smaller than 10
    {
        int temp = myarray[k]; // put myarray[k] to temp
        int j = k - 1; // put k-1 to j
        while (j >= 0 && temp <= myarray[j]) // Loop while both conditions are true: j is 0 or bigger than 0 and temp is smaller or same as myarray[j]
        {
            // the execution of the function is using swap to iterate previous variable
            myarray[j + 1] = myarray[j]; 
            j = j - 1;
        }
        myarray[j + 1] = temp; // put temp to myarray[k]
    }
```

## Task 3

- Discuss the complexity analysis of insertion sort. Refer to the link below:
  https://www.softwaretestinghelp.com/insertion-sort/

  > insertion sort uses while-loop that is more efficient than using bubble sort

## Links

- https://cpp.sh/
