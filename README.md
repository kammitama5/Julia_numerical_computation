# Julia_numerical_computation
Repo for all notes and Notebooks Julia!

- print
```
println("Hello, World!")
```

```
# - comment
```
- Concatenation strings

```
println("Hello!" * " World!") 
```

## Notes
- strings are immutable
- Precedence:
  - parentheses first
  - then exponentiation
  - multiplication and division from left to right
  - addition and subtraction from left to right

## Types
```
typeof(x)
```

```
Array{Integer(2,3)}
```
- subtypes of (Is Float64 a Subtype of Any?)
```
Float64 <: Any
```
- returns true 

## Comparison 
```
==(2, 2.0)
``` 
- returns true
```
===(2, 2.0)
``` 
- returns false
```is(2, 2.0)``` is the same as ```===``` and does bit-level comparison


## Data Analysis

- read in data
```
file = readdlm('file.csv',sep)
```


