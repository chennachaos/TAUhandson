* This version demonstrates dynamic instrumentation using TAU.
* In this version we build the exe using mpicxx. No `-g` flag as well.
* Environment variables TAU_SAMPLING and TAU_CALLPATH are set to 1.
* We prepend `tau_exec` to the exe, along with some options ( -T mpi,papi,pdt).
* This does not produce any useful profiling data related to the user's source code. Only MPI calls are profiled.
* The only difference in the output is that the contexts are referenced with "=>". Check the output of `pprof` between this version and `ex1`.

