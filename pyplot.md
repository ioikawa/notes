# PyPlot.jl

## Links
- [Matplotlib cheatsheets and handouts](https://matplotlib.org/cheatsheets/)

## Plot
```julia
using PyPlot
x = -pi:0.1:pi
y = sin.(x)
grid()
legend()
xlabel("x")
ylabel("y")
plot(x, y, lw = 5, ls = "--", color="green", label="sin(x)")
```

## linestyle 
- `"-"` ────── solid
- `":"  ...... dotted
- "--"  ------ dashed
