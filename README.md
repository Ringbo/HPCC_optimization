# HPCC_optimization

## feature
more than 9x faster than baseline(Using CUDA lib)

## requirements
* FTW3.3.8
* CUDA 9 or 10
* Intel MKL or cblas lib
* MPI lib (e.g., Mpich, openMPI)

## compile FFTW3
```sh
./configure --prefix=/home/ringbo/hpcc/fftw-3.3.8/install --enable-mpi --enable-avx512 --enable-sse2 --enable-generic-simd256 --enable-single
```
