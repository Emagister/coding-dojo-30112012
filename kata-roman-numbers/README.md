# Emagister Coding Dojo -- 30/11/2012 #

## Kata Roman Numerals ##

**Difficulty level** -- easy

### Problem description ###

#### PART I ####

The Romans were a clever bunch. They conquered most of Europe and ruled it for hundreds of years.
They invented concrete and straight roads and even bikinis[1]. One thing they never discovered
though was the number zero. This made writing and dating extensive histories of their exploits
slightly more challenging, but the system of numbers they came up with is still in use today.
For example the BBC uses Roman numerals to date their programmes.

The Romans wrote numbers using letters - I, V, X, L, C, D, M. (notice these letters have lots of
straight lines and are hence easy to hack into stone tablets)

The Kata says you should write a function to convert from normal numbers to Roman Numerals: eg

     1 --> I
     10 --> X
     7 --> VII

For a full description of how it works, take a look at [this useful reference website](http://www.novaroma.org/via_romana/numbers.html)

There is no need to be able to convert numbers larger than about 3000. (The Romans themselves
didn't tend to go any higher)

Note that you can't write numerals like "IM" for 999. Wikipedia says: Modern Roman numerals ...
are written by expressing each digit separately starting with the left most digit and skipping
any digit with a value of zero. To see this in practice, consider the ... example of 1990. In 
Roman numerals 1990 is rendered: 1000=M, 900=CM, 90=XC; resulting in MCMXC. 2008 is written as
2000=MM, 8=VIII; or MMVIII.

#### PART II ####

Write a function to convert in the other direction, ie numeral to digit

### Suggested Test Cases ###

Exercise left to the reader. You could use 1999 as an acceptance test.