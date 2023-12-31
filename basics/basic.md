## Variables in Swift
1. Integer
2. Double
3. Float
4. Boolean
5. String

## Creating variables 
```swift
var num = 5
var num : Int
```
## Naming Convention
In swift, we use camel case convention for writing the variables and functions
```swift
var pressedButton
var randomNumber
```
## String Interpolation
```swift
print("The sum is \(2+3)")
```

## Constants
For a varaible, whose value will remain constant throughout the code we use let keyword
```swift
let age = 19
```

## Arrays
Arrays are one of the most commonly used data types in an app. You use arrays to organize your app’s data.
```swift
// An array of 'Int' elements
let oddNumbers = [1, 3, 5, 7, 9, 11]


// An array of 'String' elements
let cities = ["Lucknow", "Delhi", "Mumbai", "Pune"]
```
## Randomization
Returns a random value within the specified range.
```swift
for num in 1...3 {       // including 3
    print(Int.random(in: 1..<100))    // not including 100
}
// Prints "53"
// Prints "64"
// Prints "5"
```
