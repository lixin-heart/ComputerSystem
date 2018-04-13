# TCPL(The C Programming Langugae, Vol2)

> [C Programming Language, Vol 2](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628)

### Chapter 1 - A Tutorial Introduction

> Exercise 1-1. Run the ``hello, world'' program on your system. Experiment with leaving out parts of the program, to see what error messages you get.

> Exercise 1-2. Experiment to find out what happens when prints's argument string contains \c, where c is some character not listed above.

```
#include <stdio.h>
main()
{
printf("hello, World \c");
}
warning: unknown escape sequence: '\c'
输出：
hello, World c
```

