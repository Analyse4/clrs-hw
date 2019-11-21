Exercises

2.2-1

Express the function $n^3/1000 - 100n^2 - 100n + 3$ in terms of $\Theta$-notation.

2.2-2

```
SELECT SORT(A)
for i = 1 to A.length - 1
    smallest = i
    for j = i + 1 to A.length
        if A[j] < A[smallest]
            smallest = j
    swap A[i], A[smallest]
```
The running time of the algorithm is $\Theta(n^2)$ for all cases