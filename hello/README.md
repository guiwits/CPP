Just a simple hello world program written in C++.

Using clang-format to format the code to LLVM style. 

To format the code:

```λ:> clang-format -style="{BasedOnStyle: llvm, IndentWidth: 2}" main.cc```

To compile:


```λ:> clang++ -Wall -Wextra -o main main.cc```
