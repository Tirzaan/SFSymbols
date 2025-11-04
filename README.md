# SF-Symbols

A complete Swift struct containing **all Apple SF Symbols** for easy, type-safe access within your SwiftUI and UIKit projects.

---

## ✨ Overview

The **SF-Symbols** package provides a single `SFSymbol` struct that includes every SF Symbol name as a `public static let` constant.  
This allows you to avoid stringly-typed symbol names and makes your code **cleaner, safer, and easier to autocomplete**.

---

## 🧩 Features

- 🚀 Access **all 6,000+** SF Symbols in a single struct  
- 💡 Full **Swift autocompletion** support  
- 🧱 Organized by category (e.g., Numbers, Flags, Shapes, Devices, etc.)  
- 💻 Compatible with **SwiftUI** and **UIKit**  
- 📦 Designed for **Swift Packages** and easy import  

---

## 💻 Example Usage

```swift
import SwiftUI
import SFSymbol

struct ContentView: View {
    var body: some View {
        Image(systemName: SFSymbol.heartFill)
            .resizable()
            .scaledToFit()
            .frame(width: 100, height: 100)
            .foregroundStyle(.red)
    }
}

