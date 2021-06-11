# Color
Represents a color
```swift
ZStack {
  Color(.systemTeal)
  Text("Hello, world!")
}
```
<img src="images/1.png" width=100>

## EdgesIgnoringSafeArea
Extend outside the safe areas of the screen:
```swift
ZStack {
  Color(.systemTeal)
    .edgesIgnoringSafeArea(.all)
  Text("Hello, world!")
}
```
<img src="images/2.png" width=100>
