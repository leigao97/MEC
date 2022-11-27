# MEC

## Compile
```
git clone https://github.com/leigao97/MEC.git
git submodule update --init --recursive
mkdir build_x86 && mkdir build_arm
sh build.sh
```
## Usage
```
./blas_conv 32 24 24 96 5 5 256
./blas_mec 32 24 24 96 5 5 256 100 1
./blas_mec 32 24 24 96 5 5 256 100 2
./blas_mec 32 24 24 96 5 5 256 100 4
./blas_mec 32 24 24 96 5 5 256 100 8
./blas_mec 32 24 24 96 5 5 256 100 16
./blas_mec 32 24 24 96 5 5 256 100 32
./blas_mec 32 24 24 96 5 5 256 100 64
```
