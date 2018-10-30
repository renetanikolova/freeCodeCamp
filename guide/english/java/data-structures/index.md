## Data Structures In Java

#### Overview

This is the definition written in <a href= "https://en.wikipedia.org/wiki/Data_structure" target="_blank" rel='nofollow'>wikipedia</a> about data structures in general:
  
  
  "A data organization, management and storage format that enables efficient access and modification. More precisely, a data structure is a collection of data values, the relationships among them, and the functions or operations that can be applied to the data."


#### Most popular data structures

- <a href = "https://docs.oracle.com/javase/7/docs/api/java/util/Set.html" target="_blank" rel='nofollow'>Set</a> [Interface]


Set is an interface which extends Collection. Unordered collection of objects, which does not keep duplicate values. Simply said set is a pair of key and value. 

Set is implemented by HashSet, TreeSet, LinkedSet.

_HashSet_ - Underlying data structure is HashTable. 
_HashTable_ is data structure, which is based on arrays. Offers fast insertion and searching. Key values are assigned to elements in a Hash Table using a Hash function. A hash function helps calculate the best index an item should go in. 
HashTable is thread safe and synchronized => it is slower. Works with multiple threads and does not allow null key. 
HashMap is not thread safe and unsynchronized => it is faster. Works with single thread and we can have one key which is null.


_Map.Entry_ – Entry is an interface inside Map interface; we use it for entrySet() – the set of entries: key + value.


_TreeSet_ - This is a set but with alphabetical/ numerical order. Again, we do not have duplicates. We have a tree:
("https://www.cs.wcupa.edu/rkline/assets/img/DS/bst2.png?1264796754")

#### More information 
- <a href='https://en.wikipedia.org/wiki/Data_structure' target='_blank' rel='nofollow'>Wikipedia - data structures</a>
