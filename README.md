## About
A simple CNN to recognize digits in MNIST with train and test code using the C++ API of PyTorch as an exercise. Credits to: https://github.com/pytorch/examples/tree/main/cpp/mnist


## Steps to follow
1. Download Libtorch from: 
```
https://download.pytorch.org/libtorch/cu121/libtorch-cxx11-abi-shared-with-deps-2.2.2%2Bcu121.zip
```

2. Build:
```
cmake -DCMAKE_PREFIX_PATH=/path/to/libtorch
make
```

3. Run training:
```
./mnist
```
