# Functions in Swift
Functions are self-contained chunks of code that perform a specific task. The main aim of functions is to reduce the repeated code of lines.
## Defining a function
```swift
func greet(person: String) -> String {
    let greeting = "Hello, " + person + "!"
    return greeting
}
```

## Calling a function
```swift
print(greet(person: "Ujjawal"))
// Prints "Hello, Ujjawal!"
print(greet(person: "Max"))
// Prints "Hello, Max!"
```

## Functions without parameters
```swift
func sayHelloWorld() -> String {
    return "hello, world"
}
print(sayHelloWorld())
// Prints "hello, world"
```

## Functions with multiple parameters
```swift
func greet(person: String, alreadyGreeted: Bool) -> String {
    if alreadyGreeted {
        return greetAgain(person: person)
    } else {
        return greet(person: person)
    }
}
print(greet(person: "Ujjawal", alreadyGreeted: true))
// Prints "Hello again, Ujjawal!"
```

## Functions without return type
```swift
func greet(person: String) {
    print("Hello, \(person)!")
}
greet(person: "Ujjawal")
// Prints "Hello, Ujjawal!"
```
