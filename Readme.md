# Jupyter notebooks solving various tasks in various mathematical software frameworks

## Purpose
I get a lot of questions on how to do solve certain tasks in various
frameworks. In the hope that these answers also may benefit others, I decided
to put them here.

## List of notebooks
* `kissat_jll_example.ipynb`: Example how to use
  [kissat](http://fmv.jku.at/kissat/) from `Julia`.
* `benchmarking.ipynb`: Some examples on how to use `BenchmarkTools.jl` for
  search algorithms in `Julia`.
* `benchmarking_convex_hull.ipynb`: How to benchmark different convex hull
  algorithms used in `polymake` via `Julia`.
* `equal_support_pm.ipynb`: How to check whether two polyhedral fans have the
  same support in `polymake`.
* `edges_jl.ipynb`: How to work with the edges of a polytope in `Julia` via
  `Polymake.jl`.
* `edges_pm.ipynb`: How to work with the edges of a polytope in `polymake`.
* `simplicial_faces_jl.ipynb`: How to get the number of simplicial faces of a
  polytope in `Julia`.
* `symmetric_fans_jl.ipynb`: How to work with polyhedral fans with a group
  action in `Julia` via `Oscar.jl`.
* `toric_geometry_jl.ipynb`: Things relevant to toric geometry in Julia via 
  `Oscar.jl`.
* `tropical_hypersurface_pm.ipynb`: Pitfalls when checking whether a point is
  contained in a tropical hypersurface in `polymake`.
* `inexact_convex_hull_OSCAR.ipynb`: What breaks when computing convex hulls
  over floating point numbers.

## References
* [Julia](https://julialang.org/)
* [Oscar.jl](https://github.com/oscar-system/Oscar.jl)
* [Polymake.jl](https://github.com/oscar-system/Polymake.jl)
* [polymake](https://polymake.org/doku.php)
