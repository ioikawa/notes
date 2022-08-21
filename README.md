# PyPlot.jl

## Links
- [Matplotlib cheatsheets and handouts](https://matplotlib.org/cheatsheets/)

## Plot
```julia
using PyPlot
x = -pi:0.1:pi
y = sin.(x)
plot(x, y, lw = 5, ls = "--", color="green")
```

## linestyle 
