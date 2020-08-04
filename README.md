# Typhon
Static Type Inference for Python.

## Status: Preliminary
Supports:
- Function with no global side effects and no parameters and returns `0`
- `int` and `float` type
- Part of `str` type
- Builtins: `input` and `print`
- Python version: Tested on 3.5, should support anywhere from 3.2 to 3.7
- No support on conditional and loop structures

## Roadmap
(Near)
- Support for conditional and loop structures
- Support for `tuple` type and handling sum types
- Support for recurrence in functions

(Moderate)
- Support for `list` type
- Memory Management
- Support for `isinstance` and `type` functions

(Far)
- Support for variable length functions, `*args` and `**kwargs`
- Support for higher order functions in python standard lib (map, reduce, filter)
- Support for higher order functions and lambdas
- Support for user defined classes (basic)