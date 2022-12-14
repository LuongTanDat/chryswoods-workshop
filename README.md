
[https://chryswoods.com/vector_c++/](https://chryswoods.com/vector_c++/)

```bash
sudo apt-get install clang-format
```

```bash
clang-format -style=microsoft -dump-config > .clang-format
```

```bash
find . -regex '.*\.\(cpp\|hpp\|cu\|c\|h\)' -exec clang-format -style=file -i {} \;
```
