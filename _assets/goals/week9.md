- Lab 7, Exercise 1:  Run batch jobs on ICDS-ACI/Roar:
   - Submit a batch job via PBS
   - Read and write data from batch job
   - Run multiple jobs using a job array
- Lab 7, Exercise 2:  Parallelize code for Distributed memory model, using patterns such as:
   + Load code and packages on worker nodes
   + Parallelize code over multiple compute nodes, using at least one of:
      - [pmap](https://docs.julialang.org/en/v1/stdlib/Distributed/#Distributed.pmap) (recommended)
      - [DistributedArrays.jl](https://juliaparallel.github.io/DistributedArrays.jl/stable/) with map and mapreduce (recommended)
      - [FLoops.jl](https://juliafolds.github.io/FLoops.jl/dev/) and `DistributedEx` (recommended)
      - [@distributed for loop](https://docs.julialang.org/en/v1/stdlib/Distributed/#Distributed.@distributed) (alternative)
      - Parallelize code using [Dagger.jl](https://juliaparallel.github.io/Dagger.jl/dev/) (alternative)
   + Explain differences in performance when using multiple processor cores on same node versus using multiple processor cores on different nodes
- Project
   - Run project code as batch job on the ICDS-ACI cluster
- Readings / Discussions
   - Evaluating the suitability of a problem for different parallel architectures
