### Learning R

Notes about R language

#### Data types

* Logical (Boolean)
* Characters (Text)
* Integers (Natural numbers)
* Numerics (Decimal numbers)

#### Example

```r
i_am_a_variable <- TRUE

i_am_false <- FALSE

my_favorite_band <- "Nine Inch Nails"

countries <- 195

body_average_temperature <- 37.1
```

To know the data type of a variable, just use the `class()` function

#### Example
```r
class(i_am_a_variable)
"logical"

class(my_favorite_band)
"character"
```


#### Variables

Use `<-` to assign a value to a variable

##### Example

`random_number <- 8`

To print out a variable

`random_number`

#### Arithmetic

Addition: `7 + 7`

Substraction: `7 - 7`

Multiplication: `3 * 7`

Division: `7 / 3`

Exponentiation: `4^2`

Modulo: `10 %% 5`

You can `add` two variables only if these are equal type

#### Example

`another_random_number <- 10`

`random_number + another_random_number`
