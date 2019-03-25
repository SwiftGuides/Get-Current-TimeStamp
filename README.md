# Get-Current-TimeStamp
This is A extension used to get current TimeStamp


Source :- https://stackoverflow.com/a/52728519/10422074

### Extension
```swift
extension Date {
    func currentTimeMillis() -> Int64! {
        return Int64(self.timeIntervalSince1970 * 1000)
    }
}

```

### Usage :- 

```swift
let timestamp = Date().currentTimeMillis()

```
