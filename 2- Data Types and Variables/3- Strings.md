# strings

## What are strings?
A Dart string is a sequence of UTF-16 code units. 
UTF stands for Unicode Transformation Format.

Let’s look at the various ways we can create strings in Dart.

```
void main() {
  // Single Quotes
  print('Using single quotes');

  // Double Quotes
  print("Using double quotes");

  // Single quotes with escape character \
  print('It\'s possible with an escape character');

  // Double quotes
  print("It's better without an escape character");
}
```
Defining a string variable
```
void main() {
    String s1 = "A String";

    print(s1);
} 
```