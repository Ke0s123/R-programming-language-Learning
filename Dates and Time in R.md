# How to Work with Date and Time in R Using the Lubridate Package
Install lubridate package found in tidyverse package
```R
install.packages("tidyverse")
library(tidyverse
library(lubridate)
```
* Types

  * A date `( "2016-08-16")`
  * A time within a day `(“20:11:59 UTC")`
  * And a date-time. This is a date plus a time `("2018-03-31 18:15:48 UTC")`
    
 * Functions
   * `today()`  to get the current date
   * `now()` to get the current date-time

R creates dates in the standard `yyyy-mm-dd` format by default.
## Converting from strings
* identify the order in which the year, month, and day appear in your dates
* Then, arrange the letters y, m, and d in the same order

For example: 
```R
ymd("2021-01-20")
mdy("January 20th, 2021")
dmy("20-Jan-2021")
```
R will return the date in `yyyy-mm-dd` format. 
