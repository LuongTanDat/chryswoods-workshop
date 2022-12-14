
[https://chryswoods.com/vector_c++/](https://chryswoods.com/vector_c++/)

```bash
sudo apt-get install clang-format
```

clang-format -style=microsoft -dump-config > .clang-format

find . -regex '.*\.\(cpp\|hpp\|cu\|c\|h\)' -exec clang-format -style=file -i {} \;