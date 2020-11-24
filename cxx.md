# C++ Style Guide
Good best practices are contained in the [C++ Core Guidelines.](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)
However, those do not dictate a particular style of formatting.

We need a consistent style of formatting.
The file [`clang-format`](./clang-format) contains a configuration for the
tool [clang-format](https://releases.llvm.org/11.0.0/tools/clang/docs/ClangFormat.html)
that can format C++ source code according to a set of rules.
This configuration is most similar to the "llvm" default style of clang-format.
You can use it by copying the file `clang-format` from this repository to
the root directory of your sources, prepending a dot to the filename (so
it will be called `.clang-format`).
Before committing your changes, run `clang-format --style=file -i
YOUR_FILENAMES`.
This will format them in-place.
The confguration file is made for clang-format version 11.0.0, so you will
need a recent version of clang.

As this project is still in an early stage, there is still the possibility
for discussion about the coding style.
Please open a ticket in the issue tracker if you feel you have a good idea.

