SPDC VennEuler.jl Presentation
========================

IJulia Presentation for the __Statistical Programming DC Meetup__

Harlan D. Harris, PhD

https://github.com/HarlanH/spdc-venneuler-julia

How to run
----------

Put your Meetup API key in a file in this directory called `apikey`.

IJulia unstallation instructions are here: https://github.com/JuliaLang/IJulia.jl

Then, in Julia:

```julia
Pkg.add("IJulia")
Pkg.add("Requests")
Pkg.add("JSON")
Pkg.add("VennEuler")

using IJulia
notebook()
```

Open the notebook, and have fun!
