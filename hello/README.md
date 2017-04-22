Just a simple hello world program written in C++.

Using clang-format to format the code to LLVM style. 

To format the code:

```λ:> clang-format -style="{BasedOnStyle: webkit, IndentWidth: 2}" main.cc```

To compile:


```λ:> clang++ -o hello main.cc```
