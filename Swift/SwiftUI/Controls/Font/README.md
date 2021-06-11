# Font

## Custom font
### Requirements
*   Custom font file must be located inside the project

    *   ![](images/1.png)
*   Info.plist must contain Key "Fonts provided by application" with array of font file names

    *   ![](images/2.png)

### Implement
```swift
Text("Hello, world!")
        .font(Font.custom("Pacifico-Regular", size: 40))
        .bold()
        .foregroundColor(.white)
```
![](images/3.png)
