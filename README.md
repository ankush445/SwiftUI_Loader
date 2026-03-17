# SwiftUI Loader 🚀

A lightweight and customizable **SwiftUI loader view** with smooth animations.
Perfect for showing loading states in modern iOS apps.

---

## ✨ Features

* ⚡ Built with SwiftUI
* 🔁 Smooth animations
* 🧩 Easy to integrate
* 📱 Lightweight and reusable

---

## 📸 Preview

<p align="center">
  <img src="Screenshots/demo.gif" width="220"/>
</p>

---

## 📦 Installation

### Swift Package Manager

Add this package:

```
https://github.com/ankush445/SwiftUI_Loader.git
```

Or:

```swift
.package(url: "https://github.com/ankush445/SwiftUI_Loader.git", from: "1.0.0")
```

---

## 🚀 Usage

```swift
import SwiftUI_Loader

struct ContentView: View {
    
    @State private var isLoading = true
    
    var body: some View {
        Text("Hello World")
            .loadingIndicator(
                isLoading: isLoading,
                message: "Loading..."
            )
    }
}
```

---

## 🛠 Requirements

* iOS 16+
* Swift 5+
* SwiftUI

---

## 📄 License

MIT License
