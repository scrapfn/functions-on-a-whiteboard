---
layout: posts
title:  Algebra of Functions and Higher Order Functions
---

### Algebra of Functions

Just like numbers, functions have some operators defined on them.

```
(f+g)(x)  =  f(x) + g(x)
(f-g)(x)  =  f(x) - g(x)
(f*g)(x)  =  f(x) * g(x)
(f/g)(x)  =  f(x) / g(x)
```

Examples:

```
let
  f(x) = x*3
  g(x) = x-2
in
  (f+g)(5) evaluates to 18
  (f-g)(5) evaluetes to 12
  (fg)(5)  evaluates to 45
  (f/g)(5) evaluates to 5
```


### Higher Order Functions

If you remember from the last post, algebraic operators can be seen as a function that has two variables. It's alot of fun if you think about the operators of functions this way too.

If `f` and `g` were functions, `f+g` is also a function. Which means `+` operator took two functions and yield another function.

Functions which involve consumpution of a function inclusive-or production of function are called **higher order functions** because as opposed to normal functions working on numbers, they work on these functions.

Having generalized the idea behind the algebra of functions, we can define our own functions on functions. Just like we defined functions on numbers.

```
(f%g)(x)  =  f(x) % g(x)
addTwo(f)(x)  =  2 + f(x)
(f○g)(x)  =  f(g(x))

The last one is probably the most interesting.

f(g(h(i(j(k(x))))))  =  (f○g○h○i○j○k)(x)
```


That's it for today. We will look at **lifts** tomorrow.
