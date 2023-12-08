## Struct
A struct in Swift is a data structure that can hold variables of different data types. It can also have functions defined in it.
```swift
struct Student {

  var name : String
  var id : Int
  var course : String

  init(name: String, id: Int, course: String){
     self.name = name
     self.id = id
     self.course = course
}

  func display(){
    print("Student[name=\(name),age=\(age), course=\(course)]")
  }
}
var student1 = Student(name: "Ujjawal", id: 065, course: "AI-DS")
print(student.name)
student.display()
```

## Classes 

```swift
class Vehicle {
    var currentSpeed = 0.0
    var description: String {
        return "traveling at \(currentSpeed) miles per hour"
    }
    func makeNoise() {
        // do nothing - an arbitrary vehicle doesn't necessarily make a noise
    }
}
```

You create a new instance of Vehicle with initializer syntax, which is written as a type name followed by empty parentheses:
```swift
let someVehicle = Vehicle()
```

### Subclass
Subclassing is the act of basing a new class on an existing class.
```swift
class SomeSubclass: SomeSuperclass {
    // subclass definition goes here
}
```
```swift
class Bicycle: Vehicle {
    var hasBasket = false
}
```

### Overriding
A subclass can provide its own custom implementation of an instance method, type method, instance property, type property that it would otherwise inherit from a superclass. This is known as overriding.
```swift
class Train: Vehicle {
    override func makeNoise() {
        print("Choo Choo")
    }
}
```
## Struct vs Class

| Struct        | Class         |
| ------------- | ------------- |
| struct MyStruct { }  | class MyClass : SuperClass { } |
| pass by value (copy of the file)  | pass by reference (original file) |
| Immutable  | Inheritance |
| Stored in Stack | Stored in Heap |
