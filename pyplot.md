# PyPlot.jl

## Links
- [Matplotlib cheatsheets and handouts](https://matplotlib.org/cheatsheets/)

## Plot
```julia
using PyPlot
x = -pi:0.1:pi

clf()   # clear
grid()
xlabel("x")
ylabel("y")
xticks(-pi:0.5pi:pi)

plot(x, sin.(x), lw = 5, ls = "dashed", color="green", label="\$\\sin(x)\$")
plot(x, sin.(x).^2, lw = 2, color="blue", label="\$\\sin^2(x)\$")

legend()
```

## linestyle 
- `"-"` ────── solid
- `":"`  ...... dotted
- `"--"`  ------ dashed

## Marker
- `"."`  。small circle
- `"o"`  ●circle 
- `"s"`  ■square 
- `"X"`  ✖cross 
- `"P"`  ➕plus symbol
- `"*"`  ★star 
