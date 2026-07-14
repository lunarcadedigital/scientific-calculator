# Scientific Calculator

A modern Scientific Calculator Android application built with Kotlin, Jetpack Compose, and Material Design 3.

## Features

### Calculator Modes
- **Basic Mode:** Standard arithmetic operations (+, −, ×, ÷, %, ±)
- **Scientific Mode:** Advanced functions including:
  - Trigonometric: sin, cos, tan
  - Logarithmic: log (base 10), ln (natural)
  - Powers: x², xⁿ, √
  - Constants: π, e
  - Factorial: n!
  - Parentheses support

### Multi-Language Support
- English (default)
- Bahasa Indonesia
- Language switcher in Settings

### Theming
- Light mode
- Dark mode
- System default (follows device settings)
- Material Design 3 dynamic colors (Android 12+)

### Architecture
- MVVM (Model-View-ViewModel)
- Jetpack Compose UI
- DataStore for preferences persistence
- Navigation Compose for screen routing

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Kotlin |
| UI | Jetpack Compose |
| Design | Material Design 3 |
| Architecture | MVVM |
| Navigation | Navigation Compose |
| Storage | DataStore Preferences |
| Build | Gradle Kotlin DSL |
| Min SDK | 24 (Android 7.0) |
| Target SDK | 34 (Android 14) |

## Project Structure

```
app/src/main/java/com/calculator/scientific/
├── MainActivity.kt                    # Entry point
├── navigation/
│   └── NavGraph.kt                    # Navigation routes
├── ui/
│   ├── theme/
│   │   ├── Color.kt                   # Color definitions
│   │   ├── Theme.kt                   # Material 3 theme
│   │   └── Type.kt                    # Typography
│   ├── screens/
│   │   ├── MainScreen.kt              # Calculator screen
│   │   └── SettingsScreen.kt          # Settings screen
│   └── components/
│       ├── CalculatorButton.kt        # Reusable button
│       ├── DisplayPanel.kt            # Expression display
│       ├── BasicKeypad.kt             # Basic mode layout
│       ├── ScientificKeypad.kt        # Scientific mode layout
│       └── ModeToggle.kt              # Mode switcher
├── viewmodel/
│   ├── CalculatorViewModel.kt         # Calculator logic
│   └── SettingsViewModel.kt           # Settings logic
├── engine/
│   └── CalculatorEngine.kt            # Expression parser
└── data/
    └── SettingsDataStore.kt           # Preferences storage
```

## Build & Run

1. Open project in Android Studio
2. Sync Gradle files
3. Run on device or emulator (API 24+)

```bash
./gradlew assembleDebug
```

## Calculator Engine

The `CalculatorEngine` uses a recursive descent parser to evaluate mathematical expressions with proper operator precedence:

- **Operators:** +, −, ×, ÷, %, ^
- **Functions:** sin, cos, tan, log, ln, √
- **Factorial:** n! (integer values only)
- **Constants:** π, e
- **Parentheses:** Full support for nested expressions

## 👥 Contributors

| Name | Division | Role |
|------|----------|------|
| Dimas Purnomo | 🔬 Research | Requirement analysis & tech research |
| Sari Wulandari | 🔬 Research | Dependency audit & technology scouting |
| Aditya Nugraha | 🔬 Research | Competitor analysis |
| Eko Prasetyo | 🏗️ Architect | System architecture & data flow design |
| Dewi Sartika | 🏗️ Architect | Database schema design |
| Bambang Lesmono | 🏗️ Architect | API specification & integration design |
| Dani Ramdani | 🤖 Android | Kotlin/Jetpack Compose development |
| Joko Susilo | 🤖 Android | Business logic & ViewModels |
| Budi Santoso | 🤖 Android | Local storage & DataStore |
| Rizky Fauzi | 🤖 Android | Background services & lifecycle |
| Prasetyo Hadi | 🧪 QA | Quality assurance & testing |
| Melani Putri | 🧪 QA | Test execution & verification |
| Yuda Saputra | 🧪 QA | Bug reporting & regression testing |
| Ratna Sari Dewi | 🧪 QA | Test documentation |
| Rizal Fadillah | 🔧 Fixing | Android bug fixes & patches |
| Nina Salsabila | 📣 Marketing | Content & copywriting |
| Indah Permatasari | 📣 Marketing | Logo & app icon design |
| Budi Hartono | 🚀 Release | CI/CD pipeline & build automation |
| Roro Ayuningtyas | 🚀 Release | README & documentation packaging |
| Siti Rahayu | 🚀 Release | Changelog & versioning |
| Ahmad Fauzi | 🚀 Release | Release monitoring |
| Slamet Riyadi | 📦 Archive | Documentation & archival |
| Rina Marlina | 📦 Archive | Knowledge base management |
| Wawan Setiawan | 📦 Archive | Backup & asset library |

---

## 📄 License

MIT License

Copyright (c) 2026 Lunarcade Digital

---

<p align="center">
  <sub>© 2026 Lunarcade Digital. All rights reserved.</sub>
</p>
