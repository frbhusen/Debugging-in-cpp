
# Debugging in C++
## Usage/Examples

### How to use it :
```cpp

// The <bits/stdc++.h> library has all the needed libraries for coding in C++
#include <bits/stdc++.h>
// We use "using namespace std;" instead of writing std:: every time
using namespace std;

/*
    Checking if the code is running localy or on an online
     judging system to include the custom Debugging library.
*/
#ifndef ONLINE_JUDGE
#include <Debug.h>;
#else
#define debug(...) 4
#endif

int main(){
    int a = 5;
    bool b = 1;
    char c = 'c';
    double d = 1.52;
    debug(a, b, c, d, e);
}

```

## Output:
### [a, b, c, d, e] = [5, true, 'c', 1.52]

### All the working data types    
- int
- char
- double
- float
- long long
- unsinged <data type>
- string
- vector
- set
- map
- pair
- multiset
- #### The debug works with collections types which you can iterate by 
   ```c++
   for(auto it : a)
   ```
### Data types that does not work

- stack
 - queue
 - deque
 - priority_queue
 
 - #### The debug won't work with collections types which you can't iterate by

   ```c++
   for(auto it : a)
   ```
   

## Coder and Repository Author

- [@frbhusen](https://github.com/frbhusen)

## Debugger Coder
- [@Tourist](https://codeforces.com/profile/tourist)
