# CPP STL

This repository demonstartes the cpp standard library.

![img](stl_map.png)

## Heap

- std::make_heap(begin(numbers), end(numbers)) <make a heap into an array>
- std::push_heap(begin(numbers), end(numbers)) <put new element into the array heap>
- std::pop_heap(begin(numbers), end(numbers)) <pop the first element in the array heap>

## Sorting

- std::sort() <sort everything in order>
- std::partial_sort() <sort up to the defined position, anything further is unspecified order>
- std::nth_element() <sort everything smaller than the n element at the left, and everything larger at the left, both sides order is unspecified>
- std::sort_heap <repeated calling pop heap and obtain a sort>
- std::inplace_merge <takes two sorted part of vector and combines them into a sorted vector>

## Partitioning

- std::partition() <baesd on the predicate, and placing all the predicate ones infront and all others behind>
- std::partition_point() <retrieve the partition point in the vector>

## Other Permutation

- std::rotate() <take last element and place at the begining of a vector>
- std::shuffle <shuffle elements order in a vector randomly>
- std::nex_permutation <obtain next permutation of a given vector>
- std::prev_permutation <obtain previous permutation of a given vector>
- std::reverse <reverse the order of a vector>

## Secret Runes

Use along with other std algorithms to generate new algorihms.

### Partitioning-Sort-Heap

### Stable

- std::stable_sort() <it does what the algorithm does but keeps the order>
- std::stable_partition() <it does what the algorithm does but keeps the order>

### Is

- std::is_sorted() <true if sorted>
- std::is_partitioned() <true if is partitioned>
- std::is_heap() <true if is heap>

### Is Util

- std::is_sorted_until() <returns an iterator where the first position where that predicate does not holds true anymore>
- std::is_partitioned_until() <returns an iterator where the first position where that predicate does not holds true anymore>
- std::is_heap_until() <returns an iterator where the first position where that predicate does not holds true anymore>

## Reference

- [video_link](https://www.youtube.com/watch?v=2olsGf6JIkU)
