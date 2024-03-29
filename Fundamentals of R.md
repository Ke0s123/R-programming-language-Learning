# Fundamentals of Programming using R
## The basic concepts of R ...
* Functions

  A body of reusable code used to perform specific tasks in R
  * Argument

    Information that a function in R needs in order to run
* Variables

  A representation of a value in R that can be stored for use later during programming
    * A variable name should start with a letter and can also contain numbers and underscores
    * case sensitve
    * example:
```R
first_variable <- "this is a variable"
second_variable <- 2.5

<- is the assignment operator
```
* Data types

  there are many different types of data types in R

   * logical, integer, double, character (which contains strings), complex, and raw.

  
* Vectors

  A group of data elements of the same type stored in a sequence in R

```R
vec_1 <- c(10,40.5,71)
```
* Pipes

  A tool in R for expressing a sequence of multiple operations, represented with `%>%`

```R
Plantgrowth %>% filter(dose == 0.5) %>% arrange(len)
```
* Comments

    Help make code more readable

```R
# Use the hashtag (#) at the start of the line
```
