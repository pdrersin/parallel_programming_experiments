# parallel_programming_experiments
This repository sets out a few distributed computing test problems to be solved with HPX and compared with MPI

## Useful Links
- [Intro to Parallel Computing](https://computing.llnl.gov/tutorials/parallel_comp/) - Nice intro to all the terminology
- HPX "The C++ Standard Library for Parallelism and Concurrency"
   * [GitHub](https://github.com/STEllAR-GROUP/hpx)
   * [Website](http://stellar-group.org/libraries/hpx/)

## Supported Compilers

Just Clang 5.0. To install on Ubuntu 16.04:
- add llvm source:
    `deb http://apt.llvm.org/xenial/ llvm-toolchain-xenial main`

- Add the repository key
    `wget -O - http://apt.llvm.org/llvm-snapshot.gpg.key|sudo apt-key add -`
- After that, update your lists:
    `sudo apt-get update`
- then install
    `apt-get install clang-5.0 lldb-5.0 lld-5.0`
    
