# Scheme Basics
Please review the first two chapters of
[The Scheme Programming Language](http://www.scheme.com/tspl4/), and answer the
following questions.

## Exercise 2.2.3
Determine the values of the following expressions. Use your
Scheme system to verify your answers.
```scheme
(cons 'car 'cdr)
(list 'this '(is silly))
(cons 'is '(this silly?))
(quote (+ 2 3))
(cons '+ '(2 3))
(car '(+ 2 3))
(cdr '(+ 2 3))
cons
(quote cons)
(quote (quote cons))
(car (quote (quote cons)))
(+ 2 3)
(+ '2 '3)
(+ (car '(2 3)) (car (cdr '(2 3))))
((car (list + - * /)) 2 3)
```

## Exercise 2.2.4
`(car (car '((a b) (c d))))` yields `a`. Determine which
compositions of `car` and `cdr` applied to `((a b) (c d))` yield `b`, `c`, and `d`.

## Exercise 2.2.5
Write a Scheme expression that evaluates to the following internal list structure.

![box diagram](./images/2.gif)
