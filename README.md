# COVID Death-Rate Modelling

- Give known data on number of deaths by age, as well as total population by age

Fits a function of the form:
```
R(a) = alpha * 2^(a/tau)
```

## Notation
- **a** is an age (ranging from 0 to 100)
- **R_all** is the overall death rate
- **R_u70** is the under-70 death rate
- **P_a** means the population size for age **a**