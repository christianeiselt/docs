# Image

```swift
        Image(systemName: "paperclip.circle")
          .resizable()
          .foregroundColor(.white)
          .aspectRatio(contentMode: .fit)
          .frame(width: 150, height: 150)
          .clipShape(Circle())
          .overlay(Circle().stroke(Color.black, lineWidth: 5))
```
<img src="images/1.png" width=300>

## Apple Developer Documentation
[SwiftUI Image](https://developer.apple.com/documentation/swiftui/image)
