# 🔬 Scientific Calculator

[![Android](https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white)](https://developer.android.com/about/versions/nougat)
[![API](https://img.shields.io/badge/API-24%2B-brightgreen)](https://developer.android.com/studio/releases/platforms#7.0)
[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.20-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-2024.01-4285F4?logo=google&logoColor=white)](https://developer.android.com/jetpack/compose)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Build](https://img.shields.io/badge/Build-Passing-brightgreen)](#)
[![Tests](https://img.shields.io/badge/Tests-82%20Passed-brightgreen)](#)
[![Version](https://img.shields.io/badge/Version-1.0.0-blue)](#)

> A powerful, elegant, and bilingual scientific calculator for Android — built with modern Jetpack Compose and Material Design 3. 🧮

---

## ✨ Features

### 🔢 Dual Mode Calculator
- **Basic Mode** — Addition, subtraction, multiplication, division, percentages, and more
- **Scientific Mode** — Full suite of advanced mathematical functions

### 🔬 Scientific Functions
- **Trigonometry:** sin, cos, tan (and their inverses)
- **Logarithms:** log (base 10), ln (natural logarithm)
- **Powers & Roots:** x², xⁿ, √x, ⁿ√x
- **Constants:** π (pi), e (Euler's number)
- **Factorial:** n!
- **Parentheses** — Full support for complex nested expressions

### 🌍 Bilingual Support
- English 🇬🇧
- Bahasa Indonesia 🇮🇩
- Seamless language switching in Settings

### 🎨 Modern Material Design 3
- Beautiful, intuitive interface
- 🌙 Dark / ☀️ Light / 📱 System theme support
- Responsive design for all screen sizes

### ⚡ Smart Features
- 📋 Copy results to clipboard with one tap
- 🧮 Recursive descent parser for accurate calculations
- ✅ Proper operator precedence (PEMDAS/BODMAS)
- 🔒 100% offline — no internet required
- 🪶 Lightweight — minimal battery and storage usage
- 🛡️ Zero ads, zero tracking, zero data collection

---

## 📱 Screenshots

<div align="center">

> 📸 Screenshots coming soon!

<!-- 
| Basic Mode (Light) | Scientific Mode (Dark) | Settings |
|:---:|:---:|:---:|
| ![Basic](screenshots/basic_light.png) | ![Scientific](screenshots/scientific_dark.png) | ![Settings](screenshots/settings.png) |
-->

</div>

---

## 🚀 Installation

### 📲 Download APK

Grab the latest release APK directly from GitHub Releases:

<div align="center">

**[⬇️ Download Latest Release](https://github.com/ra60/scientific-calculator/releases/download/v1.0.0/ScientificCalculator_v1.0.0.apk)**

![APK Size](https://img.shields.io/badge/APK_Size-~11_MB-blue)
![Min SDK](https://img.shields.io/badge/Min_SDK-24-green)

</div>

### 🔧 Build from Source

**Prerequisites:**
- Android Studio Hedgehog (2023.1.1) or later
- JDK 17
- Android SDK 34

```bash
# 1. Clone the repository
git clone https://github.com/ra60/scientific-calculator.git
cd scientific-calculator

# 2. Build the release APK
./gradlew assembleRelease

# 3. Install on connected device
./gradlew installRelease
```

The signed APK will be generated at:
```
app/build/outputs/apk/release/app-release.apk
```

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|:----------:|:-------:|:-------:|
| **Kotlin** | 1.9.20 | Primary programming language |
| **Jetpack Compose** | 2024.01 BOM | Modern declarative UI toolkit |
| **Material Design 3** | Latest | UI components and theming |
| **Material Icons Extended** | Latest | Comprehensive icon library |
| **Navigation Compose** | 2.7.6 | In-app navigation |
| **DataStore Preferences** | 1.0.0 | Persistent key-value storage |
| **Lifecycle ViewModel** | 2.7.0 | MVVM architecture support |
| **Activity Compose** | 1.8.2 | Compose-Activity integration |
| **JUnit** | 4.13.2 | Unit testing framework |
| **Espresso** | 3.5.1 | UI testing framework |
| **Compose UI Test** | BOM | Compose-specific testing |

### 🏗️ Architecture

- **Pattern:** MVVM (Model-View-ViewModel)
- **Parser:** Recursive descent expression parser
- **State Management:** Compose State + ViewModel
- **Preferences:** Jetpack DataStore (not SharedPreferences)

---

## 📋 Changelog

### v1.0.0 — Initial Release 🎉
*Released: July 7, 2026*

**🆕 New Features:**
- ✅ Dual mode calculator (Basic & Scientific)
- ✅ Full scientific functions: trigonometry, logarithms, powers, factorial
- ✅ Bilingual support (English & Bahasa Indonesia)
- ✅ Material Design 3 interface
- ✅ Light, Dark, and System theme options
- ✅ Copy results to clipboard
- ✅ Responsive design for all screen sizes

**🔧 Technical:**
- ✅ Built with Jetpack Compose
- ✅ Recursive descent parser for accurate calculations
- ✅ MVVM architecture
- ✅ DataStore for persistent settings
- ✅ 82 unit tests passing
- ✅ Minimum SDK 24 (Android 7.0+)

---

## 🧪 Testing

```bash
# Run all unit tests
./gradlew test

# Run Android instrumented tests
./gradlew connectedAndroidTest

# Run with coverage
./gradlew testDebugUnitTest
```

**Test Results:** ✅ **82/82 tests passed**

---

## 🔒 Privacy

| Aspect | Status |
|:------:|:------:|
| Internet Permission | ❌ Not Required |
| Data Collection | ❌ None |
| Ads | ❌ None |
| Tracking | ❌ None |
| Third-Party Services | ❌ None |
| Offline Functionality | ✅ 100% |

> Your calculations stay on your device. Always. 🔐

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting.

---

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature idea? [Open an issue](https://github.com/ra60/scientific-calculator/issues) on GitHub!

**When reporting bugs, please include:**
- Device model and Android version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

---

## 👨‍💻 Developer

<div align="center">

**Lunarcade Digital**

[![GitHub](https://img.shields.io/badge/GitHub-@lunarcadedigital-181717?logo=github&logoColor=white)](https://github.com/lunarcadedigital)
[![Email](https://img.shields.io/badge/Email-lunarcadedigital@gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:lunarcadedigital@gmail.com)

*Crafting elegant mobile experiences* ✨

</div>

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2026 Lunarcade Digital

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

<div align="center">

**Made with ❤️ by [Lunarcade Digital](https://github.com/lunarcadedigital)**

⭐ Star this repo if you find it useful!

</div>
