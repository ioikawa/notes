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
- `":"`  ...... dotted
- "--"  ------ dashed

## Marker
- `"."`  。small circle
- `"o"`  ●circle 
- `"s"`  ■square 
- `"X"`  ✖cross 
- `"P"`  plus symbol
- `"*"`  star 
