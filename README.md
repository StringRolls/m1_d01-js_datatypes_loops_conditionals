![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# JS Datatype, Loops and Conditionals

> JS | Data types: strings, numbers, boolens, arrays, objects
 
## Main points: truthies VS falsies

The _falsies_ values (`null, undefined, false, NaN, 0, ''`) are rejected by default in conditional structures. All others (_truthys_) are accepted by default.

## Main points: objects

- Literal notation objects are composed of `key: value` pairs.

- In relation to the `keys`:
  - We speak of a **property** versus a `key` whose value is any data type except a function.
  - We talk about **method** versus a `key` whose value is a function.
  
- The access to a `key` to make a _setter_ or _getter_ use of it, is done:
  - By means of the dot notation.
  - By means of the nominal access (square brackets).
  
- The operators applicable to objects are:
  - The `in` operator allows to know the existence of a property in an object.
  - The `delete` operator allows to remove a property from an object.
  
- The iterations applicable to objects are:
  - The `for...in` loop allows to traverse the _keys_ of an object.
  - `Object.keys(obj)` allows iterating over the _keys_ of an object.
  - `Object.values(obj)` allows iterating over the values of an object.
  
 - Within an object's method the reserved word `this` refers to the object itself.
 
