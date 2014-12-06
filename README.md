# BasePi

Quick and dirty package for calculating the base pi representation of numbers to arbitrary
precision.  Works using bigfloats.  Good for debating with people on Reddit who think that integers
depend on base.

### Usage

```julia
using BasePi

basepi(2)       # Integers
basepi(4.0)     # Floats
basepi("4.61")  # Good for higher precision
basepi(2, 10)   # Explicit precision (default 20 decimal digits)
```
