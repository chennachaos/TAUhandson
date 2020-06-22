* This version demonstrates dynamic instrumentation using TAU.
* In this version we build the exe using `taucxx`. `-g` flag is not used.
* Environment variables TAU_PROFILE, TAU_SAMPLING and TAU_CALLPATH are set to 1.
* We prepend `tau_exec` to the exe, along with some options ( -T mpi,papi,pdt).
* This version produces the profiling data related to the user's source code.

