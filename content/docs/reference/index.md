+++
title = "Reference"
date = 2024-10-20T15:12:37+02:00
nowrap = true
+++

# Reference Manual

Here you will find everything you need to know about the core syntax and semantics of Lento in a quick and easy to read format, from the basics to the advanced features.

## Table of Contents

- [Reference Manual](#reference-manual)
	- [Table of Contents](#table-of-contents)
	- [1. Introduction](#1-introduction)
	- [2. Lexical Structure](#2-lexical-structure)
	- [3. Types](#3-types)
		- [3.1. Primitive Types](#31-primitive-types)
		- [3.2. Composite Types](#32-composite-types)
			- [3.2.1. Sum Types](#321-sum-types)
			- [3.2.2. Product Types](#322-product-types)
		- [3.3. Function Types](#33-function-types)
		- [3.4. Type Aliases](#34-type-aliases)
		- [3.5. Type Variables](#35-type-variables)
		- [3.6. Annotations](#36-annotations)
		- [3.7. Conversion](#37-conversion)
		- [3.8. Coercion](#38-coercion)
		- [3.9. Compatibility](#39-compatibility)
		- [3.10. Equivalence](#310-equivalence)
		- [3.11. Invariance](#311-invariance)
		- [3.12. Variance](#312-variance)
		- [3.13. Bounds](#313-bounds)
		- [3.14. Constraints](#314-constraints)
		- [3.15. Erasure](#315-erasure)
		- [3.16. Reflection](#316-reflection)
		- [3.17. About Type Inference](#317-about-type-inference)
		- [3.18. About Type Checking](#318-about-type-checking)
	- [4. Expressions](#4-expressions)
		- [4.1. Literals](#41-literals)
		- [4.2. Operators](#42-operators)
			- [4.2.1. Built-in Operators](#421-built-in-operators)
			- [4.2.2. Custom Operators](#422-custom-operators)
			- [4.2.3. Operator Precedence](#423-operator-precedence)
			- [4.2.4. Operator Associativity](#424-operator-associativity)
			- [4.2.5. Operator Position](#425-operator-position)
			- [4.2.6. Operator Overloading](#426-operator-overloading)
			- [4.2.7. Operator Symbols and Keywords](#427-operator-symbols-and-keywords)
		- [4.3. Variables](#43-variables)
		- [4.4. Functions](#44-functions)
		- [4.5. Control Flow](#45-control-flow)
			- [4.5.1. Conditional Statements](#451-conditional-statements)
			- [4.5.2. Pattern Matching](#452-pattern-matching)
			- [4.5.3. Loops](#453-loops)
		- [4.6. Structs](#46-structs)
		- [4.7. Classes](#47-classes)
		- [4.8. Lists](#48-lists)
		- [4.9. Tuples](#49-tuples)
		- [4.10. Dictionaries](#410-dictionaries)
		- [4.11. Sets](#411-sets)
		- [4.12. Generators](#412-generators)
		- [4.13. Comprehensions](#413-comprehensions)
		- [4.14. Slices](#414-slices)
		- [4.15. Evaluation Order](#415-evaluation-order)
	- [5. Error Handling](#5-error-handling)
	- [6. Modules](#6-modules)
	- [7. Standard Library](#7-standard-library)
	- [8. Appendix](#8-appendix)

## 1. Introduction

Lento is a general-purpose, strong, and statically-typed programming language designed for simplicity, performance, and safety. The language is heavily inspired by ***Rust, F#, Haskell, Swift, and Python***, and aims to combine the best features of each language into a single coherent and expressive programming model based on modern functional paradigm principles and compilation techniques.

While Lento is a new language, it draws on decades of experience in language design and implementation, and incorporates many modern language features and best practices.

It is designed to be easy to learn and use, while still providing powerful features for building complex, high-performance applications in a wide range of domains. Lento is intended to be a general-purpose language, suitable for a wide range of applications, from **system programming** to **web development**, and more.

The Lento language is designed around the following core principles:

- **Simplicity**: The language should be easy to learn and use, with a clean and consistent syntax that is intuitive to read and write.
- **Safety**: The language should provide strong guarantees about memory safety, data integrity, and error handling, to prevent common programming errors and security vulnerabilities.
- **Performance**: The language should be fast and efficient, with low-level control over memory layout, data representation, and execution behavior.
- **Expressiveness**: The language should provide powerful features for expressing complex ideas concisely and clearly, with support for functional, imperative, and object-oriented programming styles.
- **Extensibility**: The language should be extensible, with support for user-defined types, functions, and operators, to allow users to customize and extend the language to suit their needs.
- **Interoperability**: The language should be interoperable with other languages and platforms, with support for calling foreign functions, importing libraries, and sharing data between different environments.
- **Tooling**: The language should have a rich ecosystem of tools, libraries, and frameworks, to support development, testing, deployment, and maintenance of applications in a wide range of domains.
- **Community**: The language should have an active and welcoming community of users, contributors, and maintainers, who collaborate to improve the language, share knowledge, and support each other in using the language effectively.

## 2. Lexical Structure

Lento source code is written using the Unicode character set, and is case-sensitive. The following lexical elements are recognized by the Lento compiler:

- **Keywords**: Reserved words that have special meaning in the language.
- **Identifiers**: Names used to identify variables, functions, types, and other entities.
- **Literals**: Constants representing fixed values.
- **Operators**: Symbols used to perform operations on values.
- **Punctuation**: Symbols used to separate elements in the source code.
- **Comments**: Text that is ignored by the compiler.
- **Whitespace**: Spaces, tabs, and newlines used to separate tokens.

## 3. Types

Lento is a statically-typed language, which means that the type of every expression is known at compile time. The following types are supported by the Lento language:

- **Primitive Types**: Basic data types such as integers, floating-point numbers, booleans, and characters.
- **Composite Types**: Complex data types such as arrays, tuples, lists, dictionaries, and structs.
  - **Sum Types**: Types representing an inductive choice between multiple alternatives. Constructed using the `|` operator in type declarations.
  - **Product Types**: Types representing a combination of multiple values. Constructed using the `,` operator in type declarations.
- **Function Types**: Types representing functions and methods.
- **Type Aliases**: User-defined names for existing types.
- **Type Variables**: Generic types that can be specialized to different concrete types.

### 3.1. Primitive Types

Coming soon...

### 3.2. Composite Types

Coming soon...

#### 3.2.1. Sum Types

Coming soon...

#### 3.2.2. Product Types

Coming soon...

### 3.3. Function Types

Coming soon...

### 3.4. Type Aliases

Coming soon...

### 3.5. Type Variables

Coming soon...

### 3.6. Annotations

Coming soon...

### 3.7. Conversion

Coming soon...

### 3.8. Coercion

Coming soon...

### 3.9. Compatibility

Coming soon...

### 3.10. Equivalence

Coming soon...

### 3.11. Invariance

Coming soon...

### 3.12. Variance

Coming soon...

### 3.13. Bounds

Coming soon...

### 3.14. Constraints

Coming soon...

### 3.15. Erasure

Coming soon...

### 3.16. Reflection

Coming soon...

### 3.17. About Type Inference

Coming soon...

### 3.18. About Type Checking

Coming soon...

## 4. Expressions

Expressions are the building blocks of Lento programs, representing values, operations, and computations. The following sections describe the various kinds of expressions that can be used in Lento programs.

### 4.1. Literals

Literals are fixed values that are written directly in the source code. A literal can represent elements such as, numbers, strings, characters, booleans, etc. The following table lists the different kinds of literals supported by the Lento language:

| Literal Type | Example                  | Description                                                |
| ------------ | ------------------------ | ---------------------------------------------------------- |
| Integer      | `42`                     | A whole number without a fractional part.                  |
| Float        | `3.14`                   | A number with a fractional part.                           |
| String       | `"foo"`                  | A sequence of characters enclosed in double quotes.        |
| Char         | `'a'`                    | A single Unicode character enclosed in single quotes.      |
| Boolean      | `true`                   | A value representing true or false.                        |
| Unit         | `()`                     | A value representing the absence of a value.               |
| List         | `[1, 2, 3]`              | A sequence of values enclosed in square brackets.          |
| Tuple        | `(1, 2, 3)`              | A fixed-size collection of values enclosed in parentheses. |
| Dictionary   | `{ foo: 42, bar: 3.14 }` | A collection of key-value pairs enclosed in curly braces.  |
| Set          | `{ 1, 2, 3 }`            | A collection of unique values enclosed in curly braces.    |

### 4.2. Operators

Operators are symbols that represent computations on values. Lento supports a wide range of operators for arithmetic, comparison, logical, and other operations. Operators can be used in expressions to combine, transform, and manipulate values.

Lento also allow users to define custom operators using operator functions to extend the language with new operator symbols and keywords that can be used in expressions.

The following sections describe the various kinds of operators supported by the Lento language.

#### 4.2.1. Built-in Operators

Lento provides a set of built-in operators for performing common operations on values. The following table lists the different kinds of built-in operators supported by the Lento language sorted by precedence:

| Operator     | Description            | Types                                   | Example                                        |
| ------------ | ---------------------- | --------------------------------------- | ---------------------------------------------- |
| `.`          | Member access          | `Structs`, `Tuples`                     | `point.x`                                      |
| `[]`         | Indexing               | `Lists`, `Tuples`, `Dictionaries`       | `list[0]`                                      |
| `()`         | Function call          | `Functions`                             | `f(x)`                                         |
| `^`          | Exponentiation         | `Integer`, `Float`                      | `2 ^ 3`                                        |
| `!`          | Logical NOT            | `Boolean`                               | `!true`                                        |
| `-`          | Negation               | `Integer`, `Float`                      | `-42`                                          |
| `*`          | Multiplication         | `Integer`, `Float`                      | `2 * 3`                                        |
| `/`          | Division               | `Integer`, `Float`                      | `6 / 2`                                        |
| `%` or `mod` | Modulus                | `Integer`                               | `7 % 3`, `7 mod 3`                             |
| `+`          | Addition               | `Integer`, `Float`, `String`            | `2 + 3`, `"foo" + "bar"`                       |
| `-`          | Subtraction            | `Integer`, `Float`                      | `5 - 3`                                        |
| `is`         | Type check             | `Any`                                   | `x is Int`, `y is String("foo" + bar + "baz")` |
| `and`        | Logical AND            | `Boolean`                               | `true and false`                               |
| `or`         | Logical OR             | `Boolean`                               | `true or false`                                |
| `,`          | Tuple and Product Type | `Any`                                   | `(1, 2, "Hi")`, `Int, Float`                   |
| `\|`         | Sum Type               | `Sum Types`                             | `Int \| Float`                                 |
| `==`         | Equality               | `Integer`, `Float`, `String`, `Boolean` | `2 == 3`                                       |
| `!=`         | Inequality             | `Integer`, `Float`, `String`, `Boolean` | `2 != 3`                                       |
| `<`          | Less than              | `Integer`, `Float`, `String`            | `2 < 3`                                        |
| `<=`         | Less than or equal     | `Integer`, `Float`, `String`            | `2 <= 3`                                       |
| `>`          | Greater than           | `Integer`, `Float`, `String`            | `2 > 3`                                        |
| `>=`         | Greater than or equal  | `Integer`, `Float`, `String`            | `2 >= 3`                                       |

#### 4.2.2. Custom Operators

Lento allows users to define custom operators using operator functions. An operator function is linked to a regular function and a special operator symbol defined in a special compile-time step. Operator functions can support both unary and binary operators, and the operator can be used in expressions just like built-in operators.

> It is strongly recommended to use **custom operators** sparingly and only when they provide a clear and intuitive syntax for a specific operation.

The following example demonstrates how to define a custom operator function in Lento:

```swift
// Define a function
increment_by_one(x: Int) -> Int = x + 1

// Register the custom operator in the compiler
operator {
    symbol: "++",
    position: "prefix",
    precedence: 800,
    associativity: "left",
    function: increment_by_one,
    signature: Int -> Int
}

// Use the custom operator in an expression
result = 42++  // result = 43
```

Notice that the `signature` should match a variant of `increment_by_one` function. The `position` can be either `prefix`, `infix` or `ternary` *(coming soon)*, and the `associativity` can be either `left` or `right`. The `precedence` should be a number between 0 and 1000, where 0 is the lowest precedence and 1000 is the highest precedence.

#### 4.2.3. Operator Precedence

Operators in Lento have a precedence level that determines the order in which they are evaluated in an expression. Operators with higher precedence are evaluated before operators with lower precedence. The following table lists the different precedence levels of operators in Lento, from highest to lowest:

| Precedence | Class                  | Example Operators           |
| ---------- | ---------------------- | --------------------------- |
| 1100       | Postfix                | `.` `[]` `()`               |
| 1000       | Prefix                 | `!` `-`                     |
| 900        | Exponential            | `^`                         |
| 800        | Multiplicative         | `*` `/` `%`                 |
| 700        | Additive               | `+` `-`                     |
| 610        | Tuple and Product Type | `,`                         |
| 600        | Sum Type               | `\|`                        |
| 500        | Relational             | `==` `!=` `<` `<=` `>` `>=` |
| 400        | Logical AND            | `and`                       |
| 300        | Logical OR             | `or`                        |
| 200        | Conditional            | `if` `else` `match` `cond`  |
| 100        | Assignment             | `=`                         |

#### 4.2.4. Operator Associativity

Operators in Lento have an associativity that determines the order in which they are evaluated when they have the same precedence level in an expression. Operators can be left-associative, right-associative, or (special to Lento) multi-associative. The following table lists the different associativity types of operators in Lento:

| Associativity | Description                                                                | Example Operators     |
| ------------- | -------------------------------------------------------------------------- | --------------------- |
| Left          | Operators are evaluated from left to right                                 | `+` `-` `*` `/` `and` |
| Right         | Operators are evaluated from right to left                                 | `^` `or`              |
| Multi         | Operators are evaluated from left to right, but can be chained in sequence | `,` `\|`              |

#### 4.2.5. Operator Position

Operators in Lento can be prefix, infix, postfix, or ternary. The position of an operator determines how it is used in an expression:

| Position | Description                | Example Operators    | Example Expressions                      |
| -------- | -------------------------- | -------------------- | ---------------------------------------- |
| Prefix   | before its **1** operand   | `!` `-` `++`         | `!true` `-42` `++x`                      |
| Infix    | between its **2** operands | `+` `-` `*` `/` `==` | `2 + 3` `5 - 3` `6 * 2` `7 / 3` `2 == 3` |
| Postfix  | after its **1** operand    | `++` `--`            | `x++` `x--`                              |
| Ternary  | between its **3** operands | `if-else`            | `x if y else z`                          |

#### 4.2.6. Operator Overloading

Lento allows users to define multiple versions of an operator function with different argument types. This feature is known as operator overloading and allows users to define custom behavior for operators based on the types of their operands.

> It is strongly recommended to use **operator overloading** sparingly and only when it provides a clear and intuitive syntax for a specific operation.

The following example demonstrates how to define multiple versions of an operator function in Lento:

```swift
// Define a new type
type Car = {
    brand: String,
    model: String,
    year: Int
    speed: Float
}

// Define a function
add_cars(car1: Car, car2: Car) -> Car =
    Car(
        brand: car1.brand,
        model: car2.model,
        year: car1.year,
        speed: car2.speed
    )

// Register the custom operator
operator {
    symbol: "+",
    position: "infix",
    precedence: 700,
    associativity: "left",
    function: add_cars,
    signature: Car, Car -> Car
}

// Use the custom operator in an expression
car1 = Car("Toyota", "Corolla", 2020, 120.0)
car2 = Car("Honda", "Civic", 2021, 130.0)
result = car1 + car2
// result = Car("Toyota", "Civic", 2020, 130.0)
```

#### 4.2.7. Operator Symbols and Keywords

When defining custom operators, it is important to choose operator symbols and keywords that are clear, concise, and consistent with the existing syntax of the language.
Lento defines operators as either symbols or keywords.

- **Operator Symbols**: Symbols such as `+`, `-`, `*`, `/`, `==`, `!=`, etc., that represent operations on values.
- **Operator Keywords**: Keywords such as `and`, `or`, `if-else`, `is`, etc., that represent logical or relational operations.

When defining custom operators, it is recommended to use symbols for arithmetic, bitwise, and comparison operations, and keywords for logical and relational operations.

Sometimes operator symbols may include characters used in other operators, such as `+` and `++`, or `=` and `==`. In such cases, it is recommended to in these ambiguous cases to either, use the operator function directly, such as `increment` instead of `++`, or `equals` instead of `==`, or use whitespace to separate the operator symbols from other tokens in the expression to avoid confusion, such as `x + ++y` instead of `x+++y`, which can be ambiguous in prefix and postfix operators `++` and infix `+`.

So if one wants to define a custom operator for incrementing a value, it is recommended to use a different symbol, such as `++` and `+=`, or use a keyword, such as `increment` and `increment_by`.

### 4.3. Variables

Coming soon...

### 4.4. Functions

Coming soon...

### 4.5. Control Flow

Coming soon...

#### 4.5.1. Conditional Statements

Coming soon...

#### 4.5.2. Pattern Matching

Coming soon...

#### 4.5.3. Loops

Coming soon...

### 4.6. Structs

Coming soon...

### 4.7. Classes

Coming soon...

### 4.8. Lists

Coming soon...

### 4.9. Tuples

Coming soon...

### 4.10. Dictionaries

Coming soon...

### 4.11. Sets

Coming soon...

### 4.12. Generators

Coming soon...

### 4.13. Comprehensions

Coming soon...

### 4.14. Slices

Coming soon...

### 4.15. Evaluation Order

Coming soon...

## 5. Error Handling

Coming soon...

## 6. Modules

Coming soon...

## 7. Standard Library

Coming soon...

## 8. Appendix

Coming soon...

---

REST OF THE DOCUMENTATION IS COMING SOON...
