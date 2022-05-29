# Cheat Sheet - JSON
<!-- TOC -->

- [Cheat Sheet - JSON](#cheat-sheet---json)
  - [Introduction](#introduction)
  - [Examples](#examples)
  - [Data Types](#data-types)
  - [String](#string)
  - [Number](#number)

<!-- /TOC -->
## Introduction

- stands for JavaScript Object Notation
- easy to read and write.
- language agnostic data-interchange format
- filename extension is .json
- Internet Media type is application/json

## Examples

```JSON
{
  "name": "Jason", # this is `string`
  "age": 39, # this is `number`
  "height": 1.92, # this is `number.fraction`
  "gender": "M", # this is `string`
  "salary": 70000, # this is `number`
  "married": true, # this is `BOOLEAN`
  "children": [
    {"name": "Tom", "age": 9, "gender":"M"},
    {"name": "Ava", "age": 7, "gender":"F"}
  ] # this is `array`
}
```

## Data Types

Type | Description 
--- | --- 
String|Series of characters
Number | Double precision floating-point
Boolean|true or false
Array|Ordered sequence of values
Value|String, Number, Boolean, null etc
Object|Unordered collection of key/value pairs
null|Null or Empty

## String
Symbol | Description 
--- | --- 
`\"` | Double quote
`\\`|Backslash
`\/`|Forward slash
`\b`|Backspace
`\f`|Form feed
`\n`|Newline
`\r`|Carriage return
`\t`|Tab
`\u`|Trailed by four hex digits

## Number
Type | Description
--- | --- 
Integer|Digits 1-9, 0 and positive or negative
Fraction | Fractions like 0.3, 3.9
Exponent|Exponent like e, e+, e-, E, E+, E
