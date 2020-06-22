* This version demonstrates dynamic instrumentation using TAU.
* In this version we build the exe using mpicxx. No `-g` flag as well.
* No environment variables related to TAU are set.
* We prepend `tau_exec` to the exe, along with some options.
* This does not produce any useful profiling data related to the user's source code. Only MPI calls are profiled.

