## If-Else statement
An if statement is used for executing code based on the evaluation of one or more conditions.
There are two basic forms of an if statement. In each form, the opening and closing braces are required.
```swift
if condition {
   //statements
}
```

The second form of an if statement provides an additional else clause (introduced by the else keyword) and is used for executing one part of code when the condition is true and another part of code when the same condition is false.
```swift
if condition {
   statements to execute if condition is true
} else {
   statements to execute if condition is false
}
```

## Switch Statement
A switch statement allows certain blocks of code to be executed depending on the value of a control expression.
A switch statement has the following form:
```swift
switch control expression {
case 1:
    //statements
case 2:
    //statements
case 3:
    //statements  
default:
    //statements
}
```

## Dictionary 
Swift dictionary is an unordered collection of items. It stores elements in key/value pairs. Here, keys are unique identifiers that are associated with each value.
```swift
var dict : [String : Int]
```
```swift
var responseMessages = [200: "OK",
                        403: "Access forbidden",
                        404: "File not found",
                        500: "Internal server error"]
```
