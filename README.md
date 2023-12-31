# Flutter Clean Architecture with BLoC Starter Template
[![_aaladan](https://img.shields.io/twitter/follow/_aaladan?style=social)](https://twitter.com/_aaladan)

![Flutter Version](https://img.shields.io/badge/flutter-%5E3.10.1-blue.svg)
![Dart Version](https://img.shields.io/badge/dart-%5E3.0.1-blue.svg)

This is a starter template for Flutter projects that follows the Clean Architecture principles and implements the BLoC (Business Logic Component) pattern. The template is designed to provide a well-organized and scalable project structure for building robust and maintainable Flutter applications.


## Features

- Clean Architecture: The project structure is organized into layers, promoting separation of concerns and making the codebase easier to understand, test, and maintain.

- BLoC Pattern: Uses BLoC to manage the business logic and state management, providing a reactive and predictable way to handle application state changes.
- Configurable Routes: Define and manage application routes in a centralized location for easy navigation and maintenance.
- Custom Themes: Pre-configured theme support for consistent and coherent UI styling.
- Easily Accessible Assets: A dedicated folder for managing and accessing assets such as images, fonts, etc.
- Constants: Centralized location for storing application-wide constants.
- Data Layer: Manage data sources and repositories separately, making it easier to switch between data providers or update data handling logic.
- Modular Structure: Divide the app into modules for better code organization and to promote code reusability.
- Resource Management: Store and manage localizations, strings, and other resources in one place for better localization support.
- Utility Functions: A collection of utility functions that can be used throughout the application.


## Getting Started

Follow the steps below to use this starter template for your Flutter project:

1. **Clone the Repository:** Clone this repository to your local machine using `git clone`.

2. **Dependencies:** Ensure you have Flutter and Dart installed on your system. You can download them from the official Flutter website: [flutter.dev](https://flutter.dev/docs/get-started/install)

3. **Install Packages:** Navigate to the project root and run `flutter pub get` to install the required dependencies.

4. **Run the App:** Use `flutter run` to launch the application on your preferred device or simulator.


## Dependencies

This Flutter starter template utilizes the following packages:

- [go_router](https://pub.dev/packages/go_router): A declarative, package-aware router for Flutter.
- [flutter_svg](https://pub.dev/packages/flutter_svg): Provides SVG rendering capabilities for Flutter.
- [flutter_bloc](https://pub.dev/packages/flutter_bloc): Implements the BLoC pattern for state management in Flutter.
- [equatable](https://pub.dev/packages/equatable): Simplifies equality comparisons for Dart objects.
- [get_it](https://pub.dev/packages/get_it): A simple service locator for managing dependencies in Dart.
- [intl](https://pub.dev/packages/intl): Provides internationalization and localization support for Flutter apps.
- [floor](https://pub.dev/packages/floor): A SQLite abstraction for Flutter with a focus on simplicity and conciseness.
- [retrofit](https://pub.dev/packages/retrofit): A type-safe HTTP client for Dart using Retrofit annotations.
- [flutter_hooks](https://pub.dev/packages/flutter_hooks): Provides hooks for Flutter widgets for a more functional approach to stateful widgets.
- [cached_network_image](https://pub.dev/packages/cached_network_image): Caches network images and loads them efficiently in Flutter apps.
- [dio](https://pub.dev/packages/dio): A powerful HTTP client for Dart that supports Interceptors, FormData, and more.

Please refer to each package's documentation for more information on how to use them in your Flutter project.


## Project Structure

The project follows a well-defined folder structure to ensure a maintainable and organized codebase. Here is an overview of the main folders:

- **assets:** Place your application assets such as images, fonts, etc. in this folder.
- **lib/config:** Contains configurations for the application, including route management and themes.
- **lib/constants:** Holds application-wide constants.
- **lib/core:** Core modules of the application, including error handling, dependency injection, and more.
- **lib/data:** Manages data sources and repositories.
- **lib/module:** Contains feature modules of the application.
- **lib/resources:** Handles localizations and strings for the application.
- **lib/utils:** Contains utility functions used throughout the application.


## Contributions and Issues

If you find any bugs or want to contribute to this starter template, feel free to open an issue or submit a pull request on our GitHub repository.

You can also reach out to me on Twitter at [@_aaladan](https://twitter.com/_aaladan) for any questions or feedback.


## License

This starter template is open-source and available under the [MIT License](LICENSE).