# Flutter MVVM Riverpod Starter

A lightweight Flutter starter template implementing **MVVM architecture** with **Riverpod state management** and **Supabase backend**. Perfect for indie hackers and solo developers looking to quickly bootstrap their projects.

This project was inspired by the [Flutter App Architecture Guide](https://docs.flutter.dev/app-architecture/guide) and the [Starter Architecture for Flutter & Firebase](https://github.com/bizz84/starter_architecture_flutter_firebase) by [bizz84](https://github.com/bizz84).

## 🎯 Features

- **MVVM Architecture**: Clean separation of concerns
- **Riverpod State Management**: Efficient and type-safe state management solution
- **Supabase Backend**: Ready-to-use backend infrastructure
- **Dark/Light Theme**: Built-in theme support
- **Localization**: Multi-language support
- **Authentication**: Email & Social login ready
- **Routing**: Declarative routing with go_router

## 📚 Libraries & Tools

| Category             | Library                | Purpose                      |
|----------------------|------------------------|------------------------------|
| **State Management** |
|                      | `flutter_riverpod`     | Reactive state management    |
|                      | `riverpod_annotation`  | Code generation for Riverpod |
| **Backend & Auth**   |
|                      | `supabase_flutter`     | Backend as a service         |
|                      | `google_sign_in`       | Google authentication        |
|                      | `sign_in_with_apple`   | Apple authentication         |
| **Navigation**       |
|                      | `go_router`            | Declarative routing          |
| **Storage**          |
|                      | `shared_preferences`   | Local key-value storage      |
|                      | `isar`                 | Local database               |
| **Network**          |
|                      | `dio`                  | HTTP client                  |
|                      | `connectivity_plus`    | Network connectivity         |
| **UI/UX**            |
|                      | `google_fonts`         | Custom fonts                 |
|                      | `flutter_svg`          | SVG rendering                |
|                      | `shimmer`              | Loading animations           |
|                      | `lottie`               | Animation files              |
| **Utilities**        |
|                      | `easy_localization`    | Internationalization         |
|                      | `envied`               | Environment variables        |
|                      | `uuid`                 | Unique identifiers           |
| **Analytics**        |
|                      | `firebase_analytics`   | Usage tracking               |
|                      | `firebase_crashlytics` | Crash reporting              |
| **Monetization**     |
|                      | `in_app_purchase`      | In-app purchases             |

## 🏗 Project Structure

```
lib/
├── constants/         # App constants and configurations
├── environment/       # Environment variables and config files
├── extensions/        # Extension methods and helpers
├── features/          # Feature modules
│   ├── common/
│   ├── authentication/
│   ├── home/
│   ├── onboarding/
│   ├── profile/
├── routing/           # Route configurations
├── theme/             # Theme configurations
└── utils/             # Utility functions
```

## 🚀 Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/namanh11611/flutter_mvvm_riverpod.git
   ```

2. Install dependencies
   ```bash
   fvm flutter pub get
   ```

3. Run the app
   ```bash
   fvm flutter run
   ```

## 📱 Screenshots

| Light Theme                                     | Dark Theme                                    |
|-------------------------------------------------|-----------------------------------------------|
| ![Hero Light](/screenshots/HeroLight.png)       | ![Hero Dark](/screenshots/HeroDark.png)       |
| ![Profile Light](/screenshots/ProfileLight.png) | ![Profile Dark](/screenshots/ProfileDark.png) |

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
