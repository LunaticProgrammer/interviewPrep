## Analysis:

There can be multiple solutions for this problem one of the direct one is just sorting the array in non-decreasing order
and returning the element at index K

### Complexity analysis:

> T-O(NlogK) S-O(N) Via Max Heap

> T-O(NlogK) S-O(1) Via In-place sort

> T-O(N) S-O(N) Via <a href="https://en.wikipedia.org/wiki/Quickselect">QuickSelect(average)</a>

_While we can argue that QuickSelect can give a worst case of O(N^2) but if you can make trade-offs and think of an average case._

> Max-Heap > O(NlogK)

> In-Place-Sort > O(NlogN)

> QuickSelect > O(N)

## Basic Intuition

The basic idea is similar to binary search where we kept dividing the search space over and over until we found out element.

The difference here is just that we are diving seach space and looking for our solution "kth largest element".
