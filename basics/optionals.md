## Optional
An optional in Swift is basically a constant or variable that can hold a value OR no value. The value can or cannot be nil. It is denoted by appending a “?” after the type declaration. For example: 
```swift
var name: String?
```
The name string is now declared as an optional.

## Force Unwrapping
Forced Unwrapping is denoted by “!” to the optional’s name. The exclamation mark says that I know for sure that this optional has a value here, use it. For example:
```swift
var name: String?
name = “Ujjawal Singh”
print(name!)
```
## Check for nil value
```swift
if name != nil{
  print(name!)
}
```
## Optional Binding
To check if a variable has a value or not
```swift
if let actualName = name{
 print(“The name is: \(actualName)”)
} else {
 print(“name is nil”)
}
```

## Nil Coalescing Operator
Use the nil-coalescing operator (??) to supply a default value in case the Optional instance is nil. 
```swift
optional ?? default value
```

## Optional Chaining
It is used to safely access the properties and methods of a wrapped instance, use the postfix optional chaining operator (postfix ?).
```swift
optional?.property
optional?.method()
```
