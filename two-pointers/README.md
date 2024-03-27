## Two pointers

#### easy

[26. Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)

[88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)

[349. Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/)

[350. Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/)

[1.  Two Sum](https://leetcode.com/problems/two-sum)

[167.  Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted)

[202. Happy Number](https://leetcode.com/problems/happy-number/description/)


[15.  3Sum](https://leetcode.com/problems/3sum)

[18.  4Sum](https://leetcode.com/problems/4sum)

[75.  Sort Colors](https://leetcode.com/problems/sort-colors)

[283.  Move Zeroes](https://leetcode.com/problems/move-zeroes)

[763.  Partition Labels](https://leetcode.com/problems/partition-labels)

Типичные подходы:
1. указатель слева и справа 
2. быстрый медленный 
3. три указателя. Левый правый и промежуточный которым бежим 

Заметки
26. Remove Duplicates from Sorted Array
Медленный и быстрый указатель. Медленный находится всегда на последнем элементе уникального значения.
Быстрый бежит по всем дубликатам и когда не равен медленному, медленный инкрементиться, тем самым шагнув на один шаг на не уникальный элемент и берет значение быстрого т.е. становиться уникальным. 

88. https://leetcode.com/problems/merge-sorted-array/solutions/2643064/javascript-two-pointer-explanation