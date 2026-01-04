# swift-blake3
bridge swift and blake3

## Using swift-blake3

swift-blake3 is available as a Swift Package Manager package. To use it, add the following dependency in your `Package.swift`:

```swift
.package(url: "https://github.com/zhiqiangj217/swift-blake3.git", from: "0.1.0"),
```

and to your target, add `Crypto` to your dependencies. You can then `import Crypto` to get access to Swift Crypto's functionality.
