# Strings Exit Ticket

Fork and clone this repo. On your fork, answer and commit the follow questions. When you are finished, submit the link to your repo on Canvas.

## Question 1

What does combining scalars means in regards to Unicode? Select one answer.

A) Making a single character out of two or more unicode scalars

B) Multiplying a vector by a scalar

C) Putting together two elements with magnitude, but no direction

D) Combining variadic indexes into a single string

## Question 2

Select all loops below that print out each character of `myString`.

```swift
let myString = "Apple"

for character in Apple {
    print(character)
}
```

```swift
let myString = "Apple"

for character in myString.characters {
    print(myString)
}
```

```swift
let myString = "Apple"

for character in myString.characters {
    print(character)
}
```

```swift
let myString = "Apple"
let start = myString.startIndex
var i = 0

while (i < myString.count) {
    var currentIndex = myString.index(start, offsetBy: i)
    print(myString[currentIndex])
    i += 1
}
```

## Question 3

What does the code below print?  Type in what would be printed to the console.

```swift
var myString = "abcdcba"

for character in myString {
    if character <= "b" {
        print(character, terminator:"")
    }
}
```

What does the code below print? Type in what would be printed to the console.

```swift
var myString = "abc"

for character in myString {
    for _ in 0...2 {
        print(character, terminator:"")
    }
}
```
