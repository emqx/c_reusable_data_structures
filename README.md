# C Reusable Data Structures

This repository contains reusable generic data structures for C.
The data structures are generated by macros that generate structs
and functions for a specific type. For example, one can generate
one dynamic array (`dynarr.h`) holding objects of type int and another
for holding objects of type double or any other type you like.

## Currently Available Data Structures

The following data structures are currently available in the
library.

### Dynamic Array (`dynarr.h`)
  
See `test_dynarr.c` for how to use the dynamic arrays. Notice that the test
cases do not cover all available functions yet.


### Hash Bag (`hashbag.h`)
  
See `test_harhbag.c` for how to use hash bags. The same data structure can be
used for hash maps and hash sets with some creativity.


### LRU Cache (`lru.h`)
  
See `test_lru.c` for how to use lru caches.


# Testing

    make test

To run valgrind tests etc:

    make test_all

# Contribute

Send pull requests to:

https://github.com/kjellwinblad/c_reusable_data_structures


# License

Apache License 2.0

See license file for detail.

# Contact

The original author (Kjell Winblad, https://dupwin.se) can be contacted at
kjellwinblad@gmail.com
