# Personal Finance Mobile App

A comprehensive Flutter mobile application for managing personal finances with secure authentication, expense tracking, and financial insights.

## Features

- 🔐 **Secure Authentication** - Login and registration with encrypted storage
- 💰 **Expense Tracking** - Track income and expenses with categorization
- 📊 **Financial Insights** - Visual charts and analytics
- 🔒 **Data Security** - Secure storage using Flutter Secure Storage
- 🚀 **Modern Architecture** - Built with Riverpod state management and clean architecture

## Tech Stack

- **Framework**: Flutter 3.35.4
- **Language**: Dart 3.0+
- **State Management**: Riverpod
- **Navigation**: GoRouter
- **HTTP Client**: Dio
- **Storage**: Flutter Secure Storage + Shared Preferences
- **UI Icons**: Cupertino Icons + Flutter SVG

## Getting Started

### Prerequisites

- Flutter 3.0.0 or higher
- Dart 3.0.0 or higher
- iOS 12.0+ / Android API 21+

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd personal-finance-mobile
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   # iOS Simulator
   flutter run -d "iPhone 16 Plus"

   # Android Emulator
   flutter run -d android

   # Web Browser
   flutter run -d chrome
   ```

### Development

- **Hot Reload**: Save files and press `r` in the terminal
- **Hot Restart**: Press `R` in the terminal
- **DevTools**: Access debugging tools via the provided URL

## Project Structure

```
lib/
├── core/
│   ├── api/          # API client and networking
│   └── providers/    # Global providers
├── features/
│   ├── auth/         # Authentication feature
│   │   ├── data/     # Models and services
│   │   └── presentation/  # Screens and providers
│   └── home/         # Home dashboard
├── config/           # App configuration
└── main.dart         # App entry point
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
