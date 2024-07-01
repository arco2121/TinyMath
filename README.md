# TinyMath.Js

<img style="display:flex, justify-content:center" src="icon.png" width="320" height="320">

## Description

It provides a lot of usefull elements such as: 
- A rappresentation for real and complex number with arbitrary precision.
- A built-in converter between different mesure units
- An easy way to rappresent and parse easy and complex expressions
- An easy way to rappresent and parse equations

## Tools of the library

- PrimitiveType => object that can rappresent any type of number or math function.
  - new PrimitiveType("3i") => 3i
  - new PrimitiveType("3","-4") => 3-4i
  - new PrimitiveType("sin") => Sin function
  - new PrimitiveType("e") => Nepero's Costant
- new PrimitiveType("3","x") => 3x
  
- ExpressionType => object that rappresent an expression
  - new ExpressionType("2+sin(180)") => 2

- ConverterType => object that allow you to convert from a unit to another unit

  - new ConverterType("12","cm","dm") =>        1,2 dm


