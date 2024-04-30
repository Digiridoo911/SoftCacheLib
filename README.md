# SoftCacheLib

This repository contains the SoftCache library.
SoftCache is a generic, application-agnostic framework that can be used with both GPUs and FPGAs.
SoftCache exploits locality to optimize data movement in a non-intrusive manner (i.e., no changes to the algorithm are necessary) and allows the programmer to tune the cache size, cache organization, and replacement policy toward the application needs.
Each cache line can store data of any size, thereby eliminating the need for separate caches for different data types.


## Installation
To use SoftCache, simply copy the [SoftCache](./src/SoftCache/) folder to your project.

The repository also contains an example program.
Run `make all` in the [src](./src/) folder.

## References
