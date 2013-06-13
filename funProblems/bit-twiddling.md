Bit Twiddling
=============

Powers of 2
-----------

Q) Show a number is a power of 2  
A) In binary a number that is a power of 2 only has a single bit set to 1.

```c++
(x != 0) && ((x & (x - 1)) == 0);
```

Q) Show a number can be expressed as 2$$^a$$ + 2^b  
A) In binary a number that is a power of 2 only has a single bit set to 1. So this number will