---
layout: posts
title: Introduction to Functions
---

### Relations

> A relation is any set of ordered pairs.
> The set of all first components of the ordered pairs is called the domain of the relation
> and the set of all second component is called the range of the relation.
>
> -- from Intermidiate Algebra by Robert Blitzer

```
∅                 is a relation      --- A
{(1,2)}             is a relation      --- B
{(1,1),(1,2),(2,1)}      is a relation      --- C
(1,2)               is not a relation

domain of A is ∅
domain of B is {1}
domain of C is {1,2}

range of A is ∅
range of B is {2}
range of C is {1,2}
```


#### Programming Terminology

+ Sets are present in many programming languages by default.
+ Ordered pairs are often called tuples.
+ Domains and ranges can be described by types. We will come back to it some days later.



### Functions

> A function is a correspondance from first set, called the domain,
> to a second set, called the range, such that each element in the domain corresponds to
> **exactly one element** in the range.
>
> -- from Intermidiate Algebra by Robert Blitzer

```
∅                 is a function
{(1,2)}            is a function
{(1,1),(1,2),(2,1)}     is not a function
{(0,0),(1,3),(2,3)}  is a function
```

#### Caution to Programmers

 The definition of a function clearly states that a function is a relation which has a domain and a range. "functions" that perform some side-effects and returns undefined value have no range which makes them non-functions.

 The definition also states that "each element in the domain corresponds to exactly one element in the range". This ensures that you get the same result every time whenever a function is applied on a value. Therefore `random()`, `date()`, and `obj . getName()` are not functions.



### Functions as Equations and Function Notation

 Functions are usually given in terms of equation.

```
f(x) = x + 1
```

 The above code denotes that the function `f`, when applied to a value, evaluates to the value itself plus 1. The application of a function to a value is expressed as `function(value)`. Therefore `f(2)` eveluates to 3 and `f(-4)` evaluates to -3 and so on.

 Functions can have more than one variable. For example, `+` can be seen as a function that is applied to two numbers to yield another value.

### Graphing a Function

 Functions with one variable will result in a line graph.
 ![f(x)=x^2 computed using wolfram alpha]({{ site.url }}/images/article/fx_x2.png)

 Functions with more than one variable will result in a complicated multi dimention graph.
 ![f(x,z)=x^z computed usin wolfram alpha]({{ site.url }}/images/article/fxz_xz.png)
