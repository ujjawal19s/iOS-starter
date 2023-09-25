## Optional
An optional in Swift is basically a constant or variable that can hold a value OR no value. The value can or cannot be nil. It is denoted by appending a “?” after the type declaration. For example: 
```swift
var name: String?
```
The name string is now declared as an optional.

# Force Unwrapping
Forced Unwrapping is denoted by “!” to the optional’s name. The exclamation mark says that I know for sure that this optional has a value here, use it. For example:
```swift
var name: String?
name = “Ujjawal Singh”
println(name!)
```
