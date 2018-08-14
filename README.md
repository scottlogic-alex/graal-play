# Generating LLVM bitcode of mecab

```bash
cd ~/git
git clone https://github.com/taku910/mecab.git
cd mecab/mecab
CC='clang' CXX='clang' ./configure --with-charset=utf8
make
```