
```yaml
name: MyApp
options:
  bundleIdPrefix: com.example
targets:
  MyApp:
    type: application
    platform: iOS
    deploymentTarget: "17.0"
    sources: [Sources] 
```

```swift
import SwiftUI

@main
struct MyApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
```

```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        Text("Hello from Mock Mode!")
    }
}
```
