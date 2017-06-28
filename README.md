# creating conan packages

Create new package with test package folder and gitignore file

```
conan new ConanLib/0.1@demo/testing -t -gi
```

```
mkdir build && cd build
conan install .. --build missing
cmake ..
make
```
