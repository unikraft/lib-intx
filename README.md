intx for Unikraft
===================

This is the port of intx for Unikraft as external library.

## Build
intx depends on the following libraries, that need to be added to `Makefile` in this order:
* CXX standard library, e.g. `libunwind`, `compiler-rt`, `libcxxabi`, `libcxx`
* `libc`, e.g. `newlib`
* `googletest` when building the unittests

Please refer to the `README.md` as well as the documentation in the `doc/`
subdirectory of the main unikraft repository.
