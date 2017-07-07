Sorting Algorithms
==================

This is a sorting algorithms responsitory.

QuickSort
---------

Time Complexity: Best Ω(nlogn), average Θ(nlogn), worst O(n^2)

```
algorithm quicksort(A, lo, hi) is
    if lo < hi then
        p := partition(A, lo, hi)
        quicksort(A, lo, p – 1)
        quicksort(A, p + 1, hi)

algorithm partition(A, lo, hi) is
    pivot := A[hi]
    i := lo - 1    
    for j := lo to hi do
        if A[j] ≤ pivot then
            i := i + 1
            if i ≠ j then
                swap A[i] with A[j]
    return i
```

* [C](https://github.com/HurinHall/Sort-Algorithm/blob/master/QuickSort/QuickSort.c)
* [Java](https://github.com/HurinHall/Sort-Algorithm/blob/master/QuickSort/QuickSort.java)
* [Python](https://github.com/HurinHall/Sort-Algorithm/blob/master/QuickSort/QuickSort.py)
* [Ruby](https://github.com/HurinHall/Sort-Algorithm/blob/master/QuickSort/QuickSort.rb)
* [PHP](https://github.com/HurinHall/Sort-Algorithm/blob/master/QuickSort/QuickSort.php)
* [Bash](https://github.com/HurinHall/Sort-Algorithm/blob/master/QuickSort/QuickSort.sh)
