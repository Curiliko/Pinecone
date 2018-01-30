# Strings and Input

In Pinecone, like in many languages, a string is a series of characters of any length. To make a string, simply surround some text in double quotes:

```
myString: "this is a string!!!"
```

## Operators and Functions

Like other types, there are various operators and functions that can be applied to strings.
* `=` checks if two strings are exactly the same.
* `+` combines two strings.
* `stringName.len` returns the length of that string.
* `68.ascii` will return a string one character long containing the ascii value of the int.
* `stringName.sub: start, end` returns a substring. I use start and end instead of start and length because start and length is stupid.
* `84.String` will return a string with that number in base 10 (aka, normal). This can be done for Ints, Dubs, and Bools.

## String input

You can get a string as an input from the user. To do this, call `String.input`. This will block execution until they type something in and press enter, at which time the function will return a string. If you want to give the user a prompt, call the function like this: `"please enter some input: ".input`.

[index](index.md) | [next: Structures and Functions ->](4_structures_and_functions.md)
