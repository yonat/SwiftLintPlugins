# SwiftLint Plugins

[SwiftLint](https://github.com/realm/SwiftLint) package build plugin.

## Usage:

```swift
// swift-tools-version: 5.6

import PackageDescription

let package = Package(
    name: "MyPackage",
    // ...
    dependencies: [
        .package(url: "https://github.com/juozasvalancius/SwiftLintPlugins.git", branch: "main"),
        // ...
    ],
    targets: [
        .target(
            name: "MyPackage",
            plugins: ["SwiftLint"]
        ),
        // ...
    ]
)
```
