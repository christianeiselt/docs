# Font

## Apple Developer Documentation
[SwiftUI Font](https://developer.apple.com/documentation/swiftui/font)

## Custom font
### Requirements
Custom font file must be located inside the project  
<img src="images/1.png" width=200>

Info.plist must contain Key "Fonts provided by application" with array of font file names  
<img src="images/2.png" width=600>

### Implementation
```swift
Text("Hello, world!")
        .font(Font.custom("Pacifico-Regular", size: 40))
        .bold()
        .foregroundColor(.white)
```
<img src="images/3.png" width=200>
