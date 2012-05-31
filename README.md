MPI Implementation of the Genetic Algorithm Library GAlib
=================================================

Installation and usage
----------------------

* Download [the latest release](https://github.com/B0RJA/GAlib-mpi/zipball/master)
* Compile with `make` (requires mpic++)
* Run the example: `mpirun -np 1 example seed 1234`

The output must be:

    GA result:
    x = 7.861659, y = 7.861659

Dive in the library usage reading the example and visit http://lancet.mit.edu/ga/ for detailed documentation.

Any problems?
-------------
Feel free to [write an issue](https://github.com/B0RJA/GAlib-mpi/issues) if you have any questions or problems.


Copyright and license
---------------------
This library is based on [GAlib](http://lancet.mit.edu/ga/), available under a BSD-style license found in the COPYRIGHT file.