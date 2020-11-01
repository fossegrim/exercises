>C is not a big language, and it is not well served by a big book.

Solutions to the exercises from K&R. They are compiled with the following flags and should not produce any warnings.
```sh
clang -std=c17 -Wall -Wextra -pedantic
```

Exercise 4-5, 4-6 and 4-10 also requires the `-lm` flag to compile.

4-12 and beyond is written in c89 and as such is compiled with the following command.
```sh
clang -std=c89 -Wall -Wextra -pedantic
```
