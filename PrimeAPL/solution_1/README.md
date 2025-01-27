# APL solution by arcfide

![Algorithm](https://img.shields.io/badge/Algorithm-wheel-yellowgreen)
![Faithfulness](https://img.shields.io/badge/Faithful-no-yellowgreen)
![Parallelism](https://img.shields.io/badge/Parallel-no-green)
![Bit count](https://img.shields.io/badge/Bits-1-green)

This is a basic implementation of a prime sieve using the algorithm initially conceived by Roger Hui and later refined by Jay Foad as documented here:

https://www.jsoftware.com/papers/50/

*Note: the build has been disabled at the request of the repository maintainers for the moment to avoid the inadvertent execution of the Dyalog APL interpreter, which is free for non-commercial use such as these demonstrations and benchmarks, but which is not Free Software.* 

## Run Instructions

You must have a working version of Dyalog APL installed. On Linux/UNIX, run `LOAD=PrimeSieveAPL.apln dyalog`. On Windows open the .dyapp file.

## Output

	arcfideSingle;6532;5.001;1;algorithm=wheel,faithful=yes,bits=1
