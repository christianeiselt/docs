# App Store Distribution

## Requirements
-   App ID with Bundle Identifier on [Apple Developer](https://developer.apple.com)
-   App (Shell) on [App Store Connect](https://appstoreconnect.apple.com)
-   Archived App
-   Certificate for App Store Code Signing

## Emerged Issues

### Distribute App in XCode

#### Code Signing: Code signing [AppName] failed (no errors in log files)
-   when using macOS 12 Beta
    -   **Solution**: Archive the product in Xcode 12 and distribute it with Xcode 13 beta.

#### Upload: Invalid App Store Icon (ITMS-90717)
-   [Stackoverflow-Question](https://stackoverflow.com/questions/46585809/error-itms-90717-invalid-app-store-icon)
-   **Solution**: Save App Store icon (1024*1024) with Preview.app and untick "Alpha".

#### Upload: Incomplete Document Type Configuration (ITMS-90788)
-   [Apple Developer Documentation](https://developer.apple.com/library/archive/documentation/General/Reference/InfoPlistKeyReference/Articles/CoreFoundationKeys.html#//apple_ref/doc/uid/TP40009249-SW1)
-   **Solution**: Add key to plist.info ("LSHandlerRank" : "none")
