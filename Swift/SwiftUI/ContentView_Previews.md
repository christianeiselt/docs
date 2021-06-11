# ContentView_Previews

## Select specific preview device
By default preview device will based on currently selected run destination.  
This can be overridden like this:
```swift
struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
      ContentView().previewDevice(PreviewDevice(rawValue: "iPad mini (5th generation)"))
    }
}
```

The supported device names can be listed using this command in terminal:
```shell
xcrun simctl list devicetypes
```x
