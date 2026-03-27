# 🛒 e-store

![e-store Cover](https://github.com/Mahmoud-Bassuni/e-store/blob/Attachment/cover.jpeg?raw=true)

**e-store** is a modular, production-ready iOS application developed as part of the **Banque Misr Mentorship Program**. It showcases a robust architecture designed for scalability, maintainability, and clean code principles.

[![Swift Version](https://img.shields.io/badge/Swift-5.7+-F05138.svg?style=flat&logo=swift)](https://swift.org)
[![Platform](https://img.shields.io/badge/Platform-iOS%2015.0+-lightgrey.svg?style=flat&logo=apple)](https://developer.apple.com/ios/)
[![Architecture](https://img.shields.io/badge/Architecture-Modular-blue.svg?style=flat)](https://developer.apple.com/documentation/swift_packages)

---

## 🚀 Features

The application provides a comprehensive e-commerce experience including:

- 🔐 **Authentication**: Secure Login and Registration flows.
- 🏠 **Home Dashboard**: Dynamic landing page featuring banners and highlights.
- 📂 **Product Catalog**: Browse products by categories.
- 📰 **Latest News**: Stay updated with the latest trends and store announcements.
- 📦 **Product Details**: Intensive information about products including pricing and descriptions.
- 🧭 **Tab Navigation**: Seamless navigation using a custom Tab Bar.

---

## 🏗 Architecture & Modularity

The project follows a **Modular Architecture** using Swift Package Manager (SPM). This ensures clear separation of concerns and faster build times.

### Modules Breakdown:
- **`e-store` (Main App)**: The entry point, containing scenes, routers, and dependency injection.
- **`Domain`**: Contains business logic, entities, and use cases.
- **`Core`**: Handles cross-cutting concerns and intermediate logic.
- **`network`**: A dedicated networking layer powered by **Alamofire**.
- **`Shared_UI`**: A library of reusable UI components and styles.
- **`e-store_foundation`**: Foundational utilities and extensions shared across the app.

---

## 🛠 Tech Stack

- **UI Framework**: UIKit (with a focus on modular UI components).
- **Networking**: [Alamofire](https://github.com/Alamofire/Alamofire) for robust API interactions.
- **Dependency Management**: CocoaPods & Swift Package Manager (SPM).
- **Backend Services**: Firebase (Integration ready).
- **Tooling**:
  - [SwiftLint](https://github.com/realm/SwiftLint) for code style consistency.
  - [SwiftGen](https://github.com/SwiftGen/SwiftGen) for type-safe resources.

---

## 📂 Project Structure

```text
.
├── Core/               # Core business logic module
├── Domain/             # Domain layer (Entities & Use Cases)
├── Shared_UI/          # Reusable UI components
├── network/            # Networking layer (Alamofire)
├── e-store_foundation/ # Foundational utilities
├── e-store/            # Main Application Workspace
│   ├── App/            # AppDelegate, SceneDelegate, App Coordinator
│   ├── ScenesScreen/   # Feature-based screens (Home, Login, etc.)
│   ├── Assembly/       # Dependency Injection Assembly
│   └── Router/         # Navigation Logic
└── Pods/               # CocoaPods dependencies
```

---

## 🏁 Getting Started

### Prerequisites
- Xcode 14.0+
- iOS 15.0+
- [CocoaPods](https://cocoapods.org/)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mahmoud-Bassuni/e-store.git
   cd e-store
   ```

2. **Install Dependencies**:
   ```bash
   # In the e-store directory
   pod install
   ```

3. **Open the Workspace**:
   ```bash
   open e-store/e-store.xcworkspace
   ```

4. **Run**:
   Select your preferred simulator and press `Cmd + R`.

---

## 🔗 Useful Links

- **API Documentation**: [FakeStoreAPI](https://fakestoreapi.com/) - Powering our e-commerce prototype.
- **Design Specs**: [Figma Design](https://www.figma.com/file/qlqfcxV2osGhV6xIHSoatM)
- **Conceptual Details**: Check out our [Wiki](https://github.com/Mahmoud-Bassuni/e-store/wiki) for advanced topics.

---

## 👥 Meet the Team

Designed and developed for the **Banque Misr Mentorship Program**.

---

*This project is for educational purposes under the Banque Misr Mentorship Program.*
