libSplash - Simple Parallel file output Library for Accumulating Simulation data using Hdf5
===========================================================================================

### Build Status by branch (master/dev)

[![Build Status Master](https://travis-ci.org/ComputationalRadiationPhysics/libSplash.png?branch=master)]
(https://travis-ci.org/ComputationalRadiationPhysics/libSplash "master")
[![Build Status Development](https://travis-ci.org/ComputationalRadiationPhysics/libSplash.png?branch=dev)]
(https://travis-ci.org/ComputationalRadiationPhysics/libSplash "dev")

Introduction
------------

**libSplash** aims at developing a HDF5-based
I/O library for HPC simulations. It is created as an easy-to-use frontend for the
standard HDF5 library with support for MPI processes in a cluster environment.
While the standard HDF5 library provides detailed low-level control, libSplash
simplifies tasks commonly found in large-scale HPC simulations, such as
iterative computations and MPI distributed processes.


libSplash is developed and maintained by the
**Center for Information Services and High Performance Computing**
([ZIH](http://tu-dresden.de/die_tu_dresden/zentrale_einrichtungen/zih)) of the
Technical University Dresden ([TUD](http://www.tu-dresden.de))
in close collaboration with the
**[Junior Group Computational Radiation Physics](http://www.hzdr.de/db/Cms?pNid=132&pOid=30354)**
at the [Institute for Radiation Physics](http://www.hzdr.de/db/Cms?pNid=132)
at [HZDR](http://www.hzdr.de/)
We are a member of the [Dresden CUDA Center of Excellence](http://ccoe-dresden.de/) that
cooperates on a broad range of scientific CUDA applications, workshops and
teaching efforts.
libSplash is actively used in the **PIConGPU** project for large-scale GPU-based particle-in-cell
simulations [picongpu.hzdr.de](http://picongpu.hzdr.de).


Software License
----------------

libSplash is licensed under the **GPLv3+ and LGPLv3+** (it is *dual licensed*).
Licences can be found in [GPL](COPYING) or [LGPL](COPYING.LESSER), respectively.

********************************************************************************


Install
-------

See our notes in [INSTALL.md](INSTALL.md).


Usage
-----

See [UserManual.pdf](doc/manual/UserManual.pdf?raw=true) for more information.
You can find detailed information on all interfaces in our
[Online Documentation](http://ComputationalRadiationPhysics.github.io/libSplash/).
Enable verbose status messages by setting the `SPLASH_VERBOSE` environment variable.


Active Team
-----------

### Maintainers* and developers

- Axel Huebl
- Felix Schmitt*
- Rene Widera

********************************************************************************

