# CHDF5
This is a Swift package manager module map for HDF5. It assumes that you installed HDF5 with a prefix of `/usr/local`, which is the default for homebrew (`brew install hdf5`).

To use add this to your `Package.swift` file dependencies: 
```swift
.Package(url: "https://github.com/trueb2/CHDF5.git", majorVersion: 1)
```
