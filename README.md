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

- types
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

## Data Analysis

- read in data
```
file = readdlm('file.csv',sep)
```


