# Brixie

Eine moderne, native mobile App für [Rebrickable.com](https://rebrickable.com) - die ultimative LEGO®-Community für Sammler und Baumeister.

## 📱 Über Brixie

Brixie bringt die gesamte Rebrickable-Experience direkt auf dein Smartphone. Verwalte deine LEGO®-Sammlung, entdecke neue MOCs (My Own Creations), und verbinde dich mit der weltweiten LEGO®-Community - alles in einer eleganten, benutzerfreundlichen App.

### ✨ Features

- **📦 Sammlung verwalten**: Verfolge deine LEGO®-Sets, Teile und Minifiguren
- **🔍 MOC-Entdeckung**: Stöbere durch tausende von benutzergenerierten Bauanleitungen
- **📋 Teilelisten**: Detaillierte Inventare für alle deine Sets
- **🎯 Build-Tracker**: Verfolge den Fortschritt deiner aktuellen Projekte
- **👥 Community**: Verbinde dich mit anderen LEGO®-Enthusiasten
- **🔄 Sync**: Nahtlose Synchronisation mit deinem Rebrickable-Account

### 🚀 Warum Brixie?

- **🚀 Cutting-Edge Tech**: Ausschließlich neueste Frameworks - SwiftUI 5.0 & Jetpack Compose
- **⚡ Maximum Performance**: Native für iOS 17+ und Android 14+ optimiert
- **🎨 Modern Design**: Material Design 3 & iOS 17 Design Language
- **🔮 Zukunftssicher**: Built with latest APIs und Entwicklungsstandards

## 📲 Download

<div align="center">

[<img src="https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us?size=250x83" alt="Download on App Store" height="60">](https://apps.apple.com/app/brixie)
   
[<img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="60">](https://play.google.com/store/apps/details?id=com.brixie.app)

</div>

## 🛠️ Technische Details

### iOS

- **Minimum Version**: iOS 17.0+
- **Framework**: SwiftUI 5.0 (pure SwiftUI - kein UIKit)
- **Architektur**: SwiftUI + Swift Concurrency (async/await)
- **Sprachen**: Swift 5.9+
- **Besondere Features**: SwiftData, Observation Framework, TipKit

### Android

- **Minimum Version**: Android 14.0 (API Level 34)
- **Framework**: Jetpack Compose (100% Compose - kein XML)
- **Architektur**: MVVM mit Compose Navigation & ViewModel
- **Sprachen**: Kotlin 2.0+ mit Kotlin Multiplatform
- **Besondere Features**: Material Design 3, Predictive Back Gestures

### Moderne Tech-Features

- **API Integration**: Ktor Client (Multiplatform) + Rebrickable REST API v3
- **Datenbank**: SwiftData (iOS) / Room mit Kotlin Multiplatform (Android)
- **Netzwerk**: Native async/await Pattern auf beiden Plattformen
- **Bildverarbeitung**: AsyncImage (iOS) / Coil Compose (Android)
- **Performance**: Metal (iOS) / Vulkan API (Android) für 3D-Visualisierungen

## 🔧 Für Entwickler

### Projekt-Setup

```bash
# Repository klonen
git clone https://github.com/[username]/brixie-app.git
cd brixie-app
```

### iOS Development

```bash
cd ios
# Xcode 15+ erforderlich
open Brixie.xcodeproj
```

### Android Development

```bash
cd android
# Android Studio Hedgehog+ erforderlich
./gradlew build
```

### Entwicklungsvoraussetzungen

- **iOS**: Xcode 15+, macOS Sonoma 14+
- **Android**: Android Studio Hedgehog+, Kotlin 2.0+
- **Shared**: Git LFS für Asset-Management

### API-Konfiguration

Erstelle eine `config.properties` Datei mit deinen Rebrickable API-Credentials:

```properties
REBRICKABLE_API_KEY=your_api_key_here
BASE_URL=https://rebrickable.com/api/v3/
```

## 🤝 Mitwirken

Wir freuen uns über Beiträge zur Brixie-Community!

### Wie kannst du helfen?

- 🐛 **Bug Reports**: Gefundene Probleme über GitHub Issues melden
- 💡 **Feature Requests**: Neue Ideen und Verbesserungsvorschläge
- 🔧 **Code Contributions**: Pull Requests für Bugfixes oder neue Features
- 🌐 **Übersetzungen**: Hilf uns, Brixie in mehr Sprachen verfügbar zu machen

### Development Guidelines

1. Fork das Repository
1. Erstelle einen Feature-Branch (`git checkout -b feature/amazing-feature`)
1. Committe deine Änderungen (`git commit -m 'Add amazing feature'`)
1. Push zum Branch (`git push origin feature/amazing-feature`)
1. Öffne einen Pull Request

## 📄 Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Siehe <LICENSE> für Details.

## 🙏 Danksagungen

- **Rebrickable Team** für die großartige API und Platform
- **LEGO® Community** für die kontinuierliche Inspiration
- **Open Source Contributors** die dieses Projekt möglich machen

## 📞 Kontakt & Support

- **Website**: [brixie-app.com](https://brixie-app.com)
- **Support**: support@brixie-app.com
- **Twitter**: [@BrixieApp](https://twitter.com/BrixieApp)
- **Discord**: [Brixie Community](https://discord.gg/brixie)

## 🏗️ Roadmap

- [ ] **v2.0**: AR Kit & ARCore Integration für 3D-Bauanleitungen
- [ ] **v2.1**: Vision Pro Support & Android XR Compatibility
- [ ] **v2.2**: AI-Powered MOC Suggestions mit Core ML & TensorFlow Lite
- [ ] **v2.3**: Spatial Computing Features
- [ ] **v2.4**: Apple Watch Ultra & Wear OS 4 Integration

-----

<div align="center">

**Brixie** - *Building dreams, one brick at a time* 🧱

*LEGO® ist eine Marke der LEGO Gruppe, die diese App nicht sponsert, autorisiert oder unterstützt.*

</div>
