## CPP Notes

Pointers
constant pointer
```cpp
int* const ptr { &x };
```
pointer to constant
```cpp
const int* ptr { &x };
```
constant pointer to a constant
```cpp
const int* const ptr { &x };
```
The pointer address and value cannot be changed.
