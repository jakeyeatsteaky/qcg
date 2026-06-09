# QCG

A clone of [QuickCG](https://lodev.org/cgtutor/quickcg.html) and perhaps some CPU Rendering.

## Getting Started


### Configuring and Building Project
#### Option A: From the cmd line
```bash
mkdir build
cd build 
cmake .. 
make
./qcg <args> // TODO need to update this
```

### Running tests

```bash
cmake --build ./build --target run # runs your executable
cmake --build ./build --target run_tests # runs gtest
```

--- 
