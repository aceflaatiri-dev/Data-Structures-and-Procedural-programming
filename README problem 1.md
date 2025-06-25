# sum_distinct Algorithm

## Description

The `sum_distinct` algorithm calculates the sum of all elements in the first set (`set1`) that **do not appear** in the second set (`set2`). The sets are represented as arrays of integers, with a maximum size of 100 elements each.

This program is written in pseudocode and demonstrates basic programming concepts such as:
- Array manipulation
- Input/output operations
- Nested loops
- Conditional checks
- Summation logic

---

## How It Works

1. The user is prompted to enter:
   - The number of elements in `set1`
   - The number of elements in `set2`
   - The individual elements of both sets

2. The algorithm then compares each element of `set1` to the elements in `set2`.

3. If an element in `set1` **does not exist** in `set2`, it is added to a running sum `s`.

4. Finally, the algorithm prints the result: the sum of elements that are unique to `set1`.

---

## Variables

- `set1`, `set2` : Arrays of integers to store the input sets.
- `n1`, `n2`     : Integers to store the number of elements in each set.
- `i`, `j`       : Loop indices.
- `s`            : Integer that stores the sum of distinct elements from `set1`.
- `a`            : Temporary variable to hold input values.
- `found`        : Boolean flag to check if an element of `set1` exists in `set2`.

---

## Example

Input:
Donner le nombre de cases de set1 : 4
Donner le nombre de cases de set2 : 3
Donner l'élément de set1 à la position 0 : 5
Donner l'élément de set1 à la position 1 : 7
Donner l'élément de set1 à la position 2 : 9
Donner l'élément de set1 à la position 3 : 11
Donner l'élément de set2 à la position 0 : 7
Donner l'élément de set2 à la position 1 : 10
Donner l'élément de set2 à la position 2 : 5

Output:
La somme des éléments distincts de set1 est : 20
