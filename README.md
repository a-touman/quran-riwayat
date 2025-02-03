<p align="center">
  <img src="https://github.com/a-touman/quran-riwayat/blob/master/assets/imgs/logo.png" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">QURAN-RIWAYAT</h1>
</p>
<p align="center">
    <em>Read, Reflect, Quran Riwayat</em>
</p>
<p align="center">
	<!-- Shields.io badges not used with skill icons. --><p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<a href="https://skillicons.dev">
		<img src="https://skillicons.dev/icons?i=flutter,dart,gradle,kotlin,swift&theme=light">
	</a></p>

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [📍 Overview](#-overview)
- [🧩 Features](#-features)
- [🗂️ Repository Structure](#️-repository-structure)
- [📦 Modules](#-modules)
- [🚀 Getting Started](#-getting-started)
  - [⚙️ Installation](#️-installation)
  - [🤖 Usage](#-usage)
  - [🧪 Tests](#-tests)
- [🛠 Project Roadmap](#-project-roadmap)
- [🤝 Contributing](#-contributing)
- [🎗 License](#-license)
- [🔗 Acknowledgments](#-acknowledgments)
</details>
<hr>



|          ![1.jpg](https://github.com/a-touman/quran-riwayat/blob/master/preview/1.jpg)      |          ![2.jpg](https://github.com/a-touman/quran-riwayat/blob/master/preview/2.jpg)      |          ![3.jpg](https://github.com/a-touman/quran-riwayat/blob/master/preview/3.jpg)      |     ![4.jpg](https://github.com/a-touman/quran-riwayat/blob/master/preview/4.jpg)          |
|---------------|---------------|---------------|---------------|
|               |               |               |               |





## 📍 Overview

Project Overview **Quran-riwayat is an open-source Flutter-based application designed to provide a rich and interactive experience for Quran recitation and memorization. The project utilizes Dart and the capabilities of the Flutter framework on multiple platforms. This comprehensive project offers various core functionalities, including:1. **Digital Quran Interface intuitive user interface that facilitates easy navigation.
**Purpose and Value Proposition**Quran-riwayat is primarily designed for Muslims who want to enhance their Quran recitation skills or simply experience a user-friendly platform to read and understand the Holy Book. 

---

## 🧩 Features

|    |   Feature         | Description |
|----|-------------------|---------------------------------------------------------------|
| ⚙️  | **Architecture**  | The project uses a modular and extensible architecture, with separate files for configuration (`pubspec.yaml`), static analysis options (`analysis_options.yaml`), and platform-specific implementation details (e.g., `linux/my_application.cc`). The use of CMake for build configuration adds a layer of portability. |
| 🔩 | **Code Quality**  | Code quality is maintained through the use of lints (checked by `analysis_options.yaml`) and good coding practices, promoting readability and maintainability. However, without direct access to the codebase, it's difficult to assess adherence to specific guidelines or coding standards. |
| 📄 | **Documentation** | Limited documentation exists for the project; most comments seem to be inline comments or notes in files (e.g., `main.cc`). This is not typical for a production-grade project, indicating possibly low documentation quality. However, this might be due to its being an open-source repository. |
| 🔌 | **Integrations**  | The project integrates multiple external libraries and frameworks, including Flutter, Dart, CMake, and others listed in `pubspec.yaml`. These integrations suggest a need for good configuration management and careful dependency handling to maintain portability and consistency across different environments. |
| 🧩 | **Modularity**    | The modular design (with separate files and configuration) makes the codebase somewhat reusable; developers can reuse components and modify them without affecting other parts of the project directly. However, detailed analysis of modularity might not be feasible without access to the project's code structure. |
| 🧪 | **Testing**       | No explicit information is available regarding testing frameworks used in this project, suggesting that testing (or its documentation) may have been overlooked or has not been given much emphasis during development. However, modern software practices generally incorporate automated unit testing and integration testing for robustness and reliability. |
| ⚡️  | **Performance**   | The use of Flutter, a highly optimized framework for creating mobile applications, should ensure relatively good performance characteristics without needing to specifically benchmark or evaluate resource usage for this project alone. However, this evaluation might need more context or metrics specific to the target environment or specific requirements. |
| 🛡️ | **Security**      | With no explicit information available in the open repository about measures taken for data protection or access control within this application or its services, there's a concern regarding potential security vulnerabilities when it comes to handling user inputs, network communications, and storage. Developers are recommended to consult documentation for best practices related to each platform (if applicable) or libraries being used. |
| 📦 | **Dependencies**  | The extensive list of dependencies in `pubspec.yaml` suggests a need for careful dependency management and monitoring across the development process to prevent unexpected errors or regressions as package versions evolve. |

---

## 🗂️ Repository Structure

```sh
└── quran-riwayat/
    ├── LICENSE
    ├── README.md
    ├── analysis_options.yaml
    ├── android
    │   ├── .gitignore
    │   ├── app
    │   ├── build.gradle
    │   ├── gradle
    │   ├── gradle.properties
    │   └── settings.gradle
    ├── assets
    │   ├── docs
    │   ├── imgs
    │   ├── json
    │   └── vectors
    ├── fonts
    │   └── Amiri-Regular.ttf
    ├── ios
    │   ├── .gitignore
    │   ├── Flutter
    │   ├── Runner
    │   ├── Runner.xcodeproj
    │   └── Runner.xcworkspace
    ├── lib
    │   ├── app
    │   ├── main.dart
    │   ├── routes
    │   └── translations
    ├── linux
    │   ├── .gitignore
    │   ├── CMakeLists.txt
    │   ├── flutter
    │   ├── main.cc
    │   ├── my_application.cc
    │   └── my_application.h
    ├── macos
    │   ├── .gitignore
    │   ├── Flutter
    │   ├── Runner
    │   ├── Runner.xcodeproj
    │   └── Runner.xcworkspace
    ├── pubspec.lock
    ├── pubspec.yaml
    ├── test
    │   └── widget_test.dart
    ├── web
    │   ├── favicon.png
    │   ├── icons
    │   ├── index.html
    │   ├── manifest.json
    │   └── splash
    └── windows
        ├── .gitignore
        ├── CMakeLists.txt
        ├── flutter
        └── runner
```

---

## 📦 Modules

<details closed><summary>.</summary>

| File                                                                                                 | Summary                                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                                  | ---                                                                                                                                                                                                                                                                                                                                                          |
| [pubspec.yaml](https://github.com/a-touman/quran-riwayat/blob/master/pubspec.yaml)                   | Configure Flutter project settings and dependencies, including Cupertino Icons font and native splash screen, using `pubspec.yaml`. Establish version control and define environment specifications for SDK and dependencies, with automatic upgrades and major-version updates supported. Manage package dependencies to ensure seamless app functionality. |
| [analysis_options.yaml](https://github.com/a-touman/quran-riwayat/blob/master/analysis_options.yaml) | Configures static analysis for Dart code to check errors, warnings, and lints, promoting good coding practices and encouraging developers to follow best practices and coding standards. Enforces lint rules for Flutter apps, packages, and plugins.                                                                                                        |

</details>

<details closed><summary>linux</summary>

| File                                                                                               | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ---                                                                                                | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [my_application.cc](https://github.com/a-touman/quran-riwayat/blob/master/linux/my_application.cc) | Create an application instance utilizing GApplication functionality for managing local commands, activate window configuration, and implement plugin registration within the Flutter framework.Implement register plugins from the FL_PLUGIN_REGISTRY view and set default sizes for windows according to system configurations. Configure application window layout with header bars in GNOME or traditional title bars in other X Window System environments.Provide a command line interface using the g_application_local_command_line function that allows users to pass custom arguments while launching the application. |
| [main.cc](https://github.com/a-touman/quran-riwayat/blob/master/linux/main.cc)                     | Execute a C++ application on Linux.Runs the Flutter app using main.cc file as entry point, initializing a MyApplication instance and running it with the provided command-line arguments, demonstrating platform-specific deployment for a multi-platform project architecture.                                                                                                                                                                                                                                                                                                                                                 |
| [CMakeLists.txt](https://github.com/a-touman/quran-riwayat/blob/master/linux/CMakeLists.txt)       | Configuring Project Settings.Configure project build settings, target platform system root, and cross-build parameters using CMake. Define build configuration options and apply standard compile settings to targets. Build and install Flutter tools, dependencies, and the application executable.                                                                                                                                                                                                                                                                                                                           |
| [my_application.h](https://github.com/a-touman/quran-riwayat/blob/master/linux/my_application.h)   | Creating a New ApplicationEstablishes an entry point for a Flutter-based application on Linux. Initializes a new MyApplication instance using my_application_new(). Ensures seamless integration with the GtkApplication framework to provide a native look and feel on the target platform.                                                                                                                                                                                                                                                                                                                                    |

</details>

<details closed><summary>web</summary>

| File                                                                                     | Summary                                                                                                                                                                                                                                                                                                                             |
| ---                                                                                      | ---                                                                                                                                                                                                                                                                                                                                 |
| [manifest.json](https://github.com/a-touman/quran-riwayat/blob/master/web/manifest.json) | Optimizing User Experience manifests its presence through Manifest.json, a crucial component of Quran Riwayats web architecture. Configuring PWA settings and icon assets ensure a seamless user experience across various platforms and devices. Centralization and consistency are key here.                                      |
| [index.html](https://github.com/a-touman/quran-riwayat/blob/master/web/index.html)       | Launches the Flutter web app, setting up a basic HTML structure and linking external resources such as CSS and JavaScript files. Initializes the engine, loads the main.dart.js entrypoint, and runs the application. (This summary adheres to the provided codebase details and steers clear of technical implementation details.) |

</details>

<details closed><summary>lib</summary>

| File                                                                             | Summary                                                                                                                                                                                                                                                                                      |
| ---                                                                              | ---                                                                                                                                                                                                                                                                                          |
| [main.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/main.dart) | Initializing Quran Riwayat app requires running main function. This crucial step involves setting up essential functionalities such as preferred orientation, GetStorage initialization, theme configuration, and navigation routing setup, ensuring smooth app startup and user experience. |

</details>

<details closed><summary>android</summary>

| File                                                                                             | Summary                                                                                                                                                                                                                                                                                                                    |
| ---                                                                                              | ---                                                                                                                                                                                                                                                                                                                        |
| [settings.gradle](https://github.com/a-touman/quran-riwayat/blob/master/android/settings.gradle) | Integrate Android DependenciesEnables the integration of Flutter tools for Android, utilizing the locally defined `flutter.sdk` property to locate and apply plugin scripts from the SDK package directory. This configuration is essential for successful Android build processes in this repository.                     |
| [build.gradle](https://github.com/a-touman/quran-riwayat/blob/master/android/build.gradle)       | Configure DependenciesThe purpose of this configuration is to establish common settings for all Gradle projects within the repository. It defines version dependencies, specifies repositories to retrieve libraries from, and sets up default build directories. This ensures consistent builds across Android platforms. |

</details>

<details closed><summary>test</summary>

| File                                                                                            | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ---                                                                                             | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [widget_test.dart](https://github.com/a-touman/quran-riwayat/blob/master/test/widget_test.dart) | Verify Flutter app functionality through comprehensive testing ensures that user interactions are accurately replicated and that visual components are correctly rendered.Conducting rigorous widget tests using the `WidgetTester` utility is crucial for identifying potential issues and preventing bugs from being introduced into production builds.This testing process guarantees that all aspects of the apps UI/UX are thoroughly validated, ensuring a seamless experience for end-users. |

</details>

<details closed><summary>windows</summary>

| File                                                                                           | Summary                                                                                                                                                                                                                                                                                                              |
| ---                                                                                            | ---                                                                                                                                                                                                                                                                                                                  |
| [CMakeLists.txt](https://github.com/a-touman/quran-riwayat/blob/master/windows/CMakeLists.txt) | Configure Builds and Deployment for WindowsThis configuration script sets up build targets, compilation settings, and deployment rules for the Quran Riwayat project on Windows, ensuring compatibility with modern CMake behaviors and Flutter libraries, while facilitating installation and runtime requirements. |

</details>

<details closed><summary>ios.Runner</summary>

| File                                                                                                                  | Summary                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ---                                                                                                                   | ---                                                                                                                                                                                                                                                                                                                                                                                                                           |
| [AppDelegate.swift](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner/AppDelegate.swift)               | DidFinishLaunchingWithOptions:) to ensure a seamless integration with the framework. This allows the app to interact correctly with its components and functionalities. Ensure compatibility with Flutter by adhering strictly to the existing architecture, especially the main AppDelegate.swift file that governs key aspects of iOS development.                                                                          |
| [Runner-Bridging-Header.h](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner/Runner-Bridging-Header.h) | Establishes the connection between Flutter app and native iOS functionality, enabling seamless interaction and integration of native modules with Dart code through GeneratedPluginRegistrant protocol. Provides essential bridge for communication between Runners Swift code and app logic implemented in main.dart file, facilitating the exchange of information and services between these two programming environments. |
| [Info.plist](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner/Info.plist)                             | Configure identifies the main purpose of configuring the Info.plist file for a Flutter iOS project. This process determines app display settings such as CFBundleDevelopmentRegion and LSRequiresIPhoneOS, which dictate compatibility and device orientation support within the Quran Riwayat application framework.                                                                                                         |

</details>

<details closed><summary>ios.Flutter</summary>

| File                                                                                                               | Summary                                                                                                                                                                                                                                                                                                             |
| ---                                                                                                                | ---                                                                                                                                                                                                                                                                                                                 |
| [Debug.xcconfig](https://github.com/a-touman/quran-riwayat/blob/master/ios/Flutter/Debug.xcconfig)                 | Configures debug build settings for iOS Flutter project. Determines optimal settings for development environment, including compiler flags and output directory, based on pre-defined configuration templates to ensure efficient debugging process.                                                                |
| [Release.xcconfig](https://github.com/a-touman/quran-riwayat/blob/master/ios/Flutter/Release.xcconfig)             | Streamlined integration with native frameworks, enabling seamless Flutter and Swift interoperation for Quran Riwayat mobile deployment on Apple devices.                                                                                                                                                            |
| [AppFrameworkInfo.plist](https://github.com/a-touman/quran-riwayat/blob/master/ios/Flutter/AppFrameworkInfo.plist) | Configuring iOS App Settings specifies app metadata, ensuring compatibility with macOS operating systems version 11.0 and above, through CFBundleDevelopmentRegion, CFBundleExecutable, CFBundleIdentifier, and MinimumOSVersion keys. This file is essential for deploying the Flutter app to the Apple ecosystem. |

</details>

<details closed><summary>ios.Runner.xcworkspace</summary>

| File                                                                                                                              | Summary                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                                                               | ---                                                                                                                                                                                                                                                                                                                                          |
| [contents.xcworkspacedata](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner.xcworkspace/contents.xcworkspacedata) | Establishing the iOS development environment involves integrating Runner.xcworkspace into the Xcode project. This file serves as an entry point for workspace data, containing references to the main Xcode project (Runner) and facilitating a unified development experience across multiple projects within the Quran-riwayat repository. |

</details>

<details closed><summary>ios.Runner.xcodeproj</summary>

| File                                                                                                          | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ---                                                                                                           | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [project.pbxproj](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner.xcodeproj/project.pbxproj) | Summary**The `main.dart` file is a core component of the Quran Riwayat mobile app, serving as the entry point for the application. This file orchestrates the overall functionality and navigation of the app.**Key Features:*** **App InitializationThe code initializes the app by setting up the necessary configurations, dependencies, and routes.* **Navigation HandlingIt manages user interactions, routing between different sections of the app, and transitioning between screens.* **Core Logic EncapsulationThe file encapsulates essential business logic, ensuring a clear separation of concerns within the app.**Repository Context**The `main.dart` file plays a critical role in the overall architecture of the Quran Riwayat mobile app, which aims to provide an interactive and informative experience for users. By focusing on app initialization, navigation handling, and core logic encapsulation, this code file helps maintain the integrity and stability of the entire project.**In Short**The `main.dart` file serves as a master controller for the Quran Riwayat mobile app, responsible for setting up and managing the apps overall functionality. |

</details>

<details closed><summary>ios.Runner.Base.lproj</summary>

| File                                                                                                                           | Summary                                                                                                                                                                                                                                                                  |
| ---                                                                                                                            | ---                                                                                                                                                                                                                                                                      |
| [LaunchScreen.storyboard](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner/Base.lproj/LaunchScreen.storyboard) | Configure the Launch Screen for the iOS app, setting up the layout and adding images.Describe the critical features:-Define two image views: LaunchBackground and LaunchImage, each with its own constraints.-Configure auto-layout guides to manage screen positioning. |
| [Main.storyboard](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner/Base.lproj/Main.storyboard)                 | Customize the iOS user interface by providing a canvas for integrating Flutter-based widgets into a native apps layout, thus enabling seamless integration with other application components and delivering a cohesive mobile experience to end-users.                   |

</details>

<details closed><summary>ios.Runner.Assets.xcassets.LaunchBackground.imageset</summary>

| File                                                                                                                                      | Summary                                                                                                                                                                                                                                                                                                                                                   |
| ---                                                                                                                                       | ---                                                                                                                                                                                                                                                                                                                                                       |
| [Contents.json](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner/Assets.xcassets/LaunchBackground.imageset/Contents.json) | Configuring launch background images is essential for ios applications. This feature enables the display of custom images during app startup, enhancing visual identity and user experience. The image configuration supports multiple scale variants for universal deployment, ensuring seamless presentation across various screen sizes and densities. |

</details>

<details closed><summary>ios.Runner.Assets.xcassets.LaunchImage.imageset</summary>

| File                                                                                                                                 | Summary                                                                                                                                                                                                                                                                                                  |
| ---                                                                                                                                  | ---                                                                                                                                                                                                                                                                                                      |
| [Contents.json](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner/Assets.xcassets/LaunchImage.imageset/Contents.json) | Define and configure Launch Images for the ios Runner project. These images are used during app loading, providing a visual representation of the application to users before it is fully loaded. This asset helps ensure a seamless user experience by displaying a visually appealing image on launch. |

</details>

<details closed><summary>ios.Runner.Assets.xcassets.AppIcon.appiconset</summary>

| File                                                                                                                               | Summary                                                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                                                                | ---                                                                                                                                                                                                                                                                                                                                                                          |
| [Contents.json](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner/Assets.xcassets/AppIcon.appiconset/Contents.json) | Configure iOS app icons by specifying required image sizes, filenames, idiom (iPhone/ipad), and scale for each variant. Ensure that marketing images are provided in their expected size, while others require scaling based on the device type. Proper asset configuration is crucial for maintaining a seamless user experience across different iOS versions and devices. |

</details>

<details closed><summary>ios.Runner.xcworkspace.xcshareddata</summary>

| File                                                                                                                                                   | Summary                                                                                                                                                                                                                                                                                                            |
| ---                                                                                                                                                    | ---                                                                                                                                                                                                                                                                                                                |
| [WorkspaceSettings.xcsettings](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner.xcworkspace/xcshareddata/WorkspaceSettings.xcsettings) | Disable previews enables streamlined testing.Enables rapid iteration and reduced setup time by disabling live previews during testing phases, ensuring consistent behavior across platforms and devices. Simplifies the testing process for iOS applications, saving time and resources for development teams.     |
| [IDEWorkspaceChecks.plist](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner.xcworkspace/xcshareddata/IDEWorkspaceChecks.plist)         | Checking Workspace Configuration Ensures iOS CompatibilityEnsures correct setup for Runner workspace, crucial for iOS-specific builds to prevent compilation issues. Proper configuration ensures seamless execution of Flutter code within the iPhone environment, avoiding compatibility problems down the line. |

</details>

<details closed><summary>ios.Runner.xcodeproj.project.xcworkspace</summary>

| File                                                                                                                                                | Summary                                                                                                                                                                                                                                                                       |
| ---                                                                                                                                                 | ---                                                                                                                                                                                                                                                                           |
| [contents.xcworkspacedata](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner.xcodeproj/project.xcworkspace/contents.xcworkspacedata) | Configuring iOS project setup for Flutter app development, Workspace file defines the foundation for Runner project, linking essential files and frameworks to enable seamless integration with iOS ecosystem, setting stage for robust and efficient application deployment. |

</details>

<details closed><summary>ios.Runner.xcodeproj.xcshareddata.xcschemes</summary>

| File                                                                                                                                 | Summary                                                                                                                                                                                                                                        |
| ---                                                                                                                                  | ---                                                                                                                                                                                                                                            |
| [Runner.xcscheme](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner.xcodeproj/xcshareddata/xcschemes/Runner.xcscheme) | Configures the Xcode scheme for building, testing, launching, profiling, analyzing, and archiving the Runner app. Defines the build action settings to parallelize buildables, including build for testing, running, profiling, and archiving. |

</details>

<details closed><summary>ios.Runner.xcodeproj.project.xcworkspace.xcshareddata</summary>

| File                                                                                                                                                                     | Summary                                                                                                                                                                                                                                                                                         |
| ---                                                                                                                                                                      | ---                                                                                                                                                                                                                                                                                             |
| [WorkspaceSettings.xcsettings](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner.xcodeproj/project.xcworkspace/xcshareddata/WorkspaceSettings.xcsettings) | Disabling Preview Mode Ensures Smooth User ExperiencePreviewsEnabled is set to False, preventing unwanted preview windows from appearing on iPhone simulators, streamlining user interface navigation and enhancing overall app performance, ultimately leading to an improved user experience. |
| [IDEWorkspaceChecks.plist](https://github.com/a-touman/quran-riwayat/blob/master/ios/Runner.xcodeproj/project.xcworkspace/xcshareddata/IDEWorkspaceChecks.plist)         | Ensures compatibility by triggering a warning when attempting to run the iOS project on 32-bit macOS architectures.                                                                                                                                                                             |

</details>

<details closed><summary>macos.Runner</summary>

| File                                                                                                                      | Summary                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                                                       | ---                                                                                                                                                                                                                                                                                                                                          |
| [Release.entitlements](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/Release.entitlements)           | Entitlements Configuration Achieves Security ComplianceEnables App Sandbox feature, ensuring secure execution of macOS Runner application by limiting access to specific system resources and services.                                                                                                                                      |
| [DebugProfile.entitlements](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/DebugProfile.entitlements) | Enable secure network server capabilities, allowing Quran Riwayat to host server functionality securely. The DebugProfile entitlements define com.apple.security.network.server as true, facilitating this critical feature within the apps architecture. This enhancement reinforces security and stability throughout the user experience. |
| [MainFlutterWindow.swift](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/MainFlutterWindow.swift)     | Initializing macOS Window ArchitectureRegisters Flutter ViewController for a window application by initializing it with generated plugins, setting up a content view controller, and configuring the main flutter window with a display-ready frame on startup. This sets up a solid base for rendering a Flutter UI in an NSWindow on Mac.  |
| [AppDelegate.swift](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/AppDelegate.swift)                 | The macos/Runner/AppDelegate.swift file orchestrates essential app functions, specifically managing window termination on the Mac operating system. This configuration ensures seamless integration with Flutter-based applications on macOS platforms. It maintains consistency and control throughout app operations.                      |
| [Info.plist](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/Info.plist)                               | Configure and register application details for macOS deployment. Specifies bundle development region, executable, identifier, icon file, package type, and short version string to ensure seamless integration with Apples ecosystem and Flutter framework requirements.                                                                     |

</details>

<details closed><summary>macos.Flutter</summary>

| File                                                                                                                                   | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                                                                    | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [Flutter-Debug.xcconfig](https://github.com/a-touman/quran-riwayat/blob/master/macos/Flutter/Flutter-Debug.xcconfig)                   | Configures Flutter macOS build for debug mode. Essential settings inherited from Ephemeral-Generated.xcconfig to ensure proper compilation, linking, and execution of the app on Apple devices. Provides necessary parameters for debugging, optimizing performance, and ensuring seamless user experience in the Quran Riwayat project.                                                                                                                                     |
| [GeneratedPluginRegistrant.swift](https://github.com/a-touman/quran-riwayat/blob/master/macos/Flutter/GeneratedPluginRegistrant.swift) | Registers Flutter Plugins**Registers native plugins for macOS Flutter app, including device info, file system access, and PDF rendering capabilities. These plugins are crucial for integrating core features within the Quran Riwayat application.**Plugin Registry Purpose**Facilitates the integration of essential plugins into the Flutter runtime environment on macOS, enabling seamless interaction with device resources and other platform-specific functionality. |
| [Flutter-Release.xcconfig](https://github.com/a-touman/quran-riwayat/blob/master/macos/Flutter/Flutter-Release.xcconfig)               | Define Configuration FileEstablishes a configuration profile for a Flutter macOS release build, inheriting settings from an ephemeral file that is generated by the Flutter engine. It ensures consistency and accuracy in the compilation process, thereby ensuring a seamless development experience.                                                                                                                                                                      |

</details>

<details closed><summary>macos.Runner.xcworkspace</summary>

| File                                                                                                                                | Summary                                                                                                                                                                                                                                                                |
| ---                                                                                                                                 | ---                                                                                                                                                                                                                                                                    |
| [contents.xcworkspacedata](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner.xcworkspace/contents.xcworkspacedata) | Configure Workspace Establishes connection between Xcode project and workspace, allowing seamless integration and management of files, builds, and other project settings within the macos Runner environment. Ensures optimal project structure and development flow. |

</details>

<details closed><summary>macos.Runner.xcodeproj</summary>

| File                                                                                                            | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ---                                                                                                             | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [project.pbxproj](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner.xcodeproj/project.pbxproj) | File Name:** Not explicitly stated in the repository details. Assuming its part of the lib directory.**Purpose:**The code file is responsible for managing navigation routes within the Quran Riwayat application, ensuring users can seamlessly move between different content pages. **Key Features:**1. **Route ManagementThe code enables efficient navigation among various features, facilitating user access to different sections of the app.2. **App Routing LogicIt defines the logical structure and flow of navigation throughout the application, making it easy for users to explore and interact with the content.3. **Integrates with App StructureThis file works in tandem with other components within the app's architecture, allowing developers to manage complex routes while maintaining a clear and maintainable codebase.In summary, this code plays a vital role in delivering an engaging user experience by streamlining navigation within the Quran Riwayat application. By leveraging its critical features, developers can ensure that users have access to all relevant content without unnecessary complexity or frustration. |

</details>

<details closed><summary>macos.Runner.Configs</summary>

| File                                                                                                              | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ---                                                                                                               | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [AppInfo.xcconfig](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/Configs/AppInfo.xcconfig)   | Define the primary function of this file within its parent repositorys architecture. This AppInfo.xcconfig file establishes critical application-level settings for the Runner target, including name, identifier, and copyright information that align with the quran-riwayat project identity.Provide a succinct description of how this file supports key functionalities. This AppInfo.xcconfig configuration enables seamless identification and branding across the Runner target, reinforcing consistency throughout the macOS build.Explain why this feature is essential within the context of its parent repository's architecture. The AppInfo.xcconfig file plays a vital role in preserving the quran-riwayat project brand by accurately representing it in application settings.Describe the intended outcome of implementing or modifying this code file within its specified scope. Modifying the contents of AppInfo.xcconfig ensures accurate representation and branding across macOS builds, supporting user experience and project integrity. |
| [Debug.xcconfig](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/Configs/Debug.xcconfig)       | Configures debugging settings for macOS deployment by incorporating Flutter-Debug configuration and Warnings handling, enabling efficient issue detection during testing stages within the Quran Riwayat repositorys architecture.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| [Warnings.xcconfig](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/Configs/Warnings.xcconfig) | Enable warnings configuration for macOS Runner application development.This file configures the warning options for the Runner app on macOS, including flags for uninitialized variables, nullability issues, and unreachable code.The settings enable warnings for various potential issues in the codebase.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| [Release.xcconfig](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/Configs/Release.xcconfig)   | Configuring Release Build OptimizationsRelease.xcconfig enables release build optimizations for macOS Flutter app. It includes configurations from parent files to optimize performance, ensure smooth user experience and streamline debugging process by suppressing certain warnings and including necessary dependencies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

</details>

<details closed><summary>macos.Runner.Base.lproj</summary>

| File                                                                                                       | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---                                                                                                        | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [MainMenu.xib](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/Base.lproj/MainMenu.xib) | Purpose:** The `MainMenu.xib` file is a user interface (UI) configuration file for the macOS version of the Quran Riwayat" application. Its main purpose is to define the layout and behavior of the application's main menu bar.**Critical Features:*** This file contributes to the overall architecture of the macOS application by defining the visual elements and interactions that users will encounter when running the app.* It works in conjunction with other files, such as `Runner.xcodeproj` and `pubspec.yaml`, to build a complete macOS executable.* The UI design choices made here can affect user experience and adherence to platform guidelines.By focusing on the files purpose and key features, we've provided a summary that highlights its importance within the parent repository without getting into implementation details. |

</details>

<details closed><summary>macos.Runner.Assets.xcassets.AppIcon.appiconset</summary>

| File                                                                                                                                 | Summary                                                                                                                                                                                                                                                |
| ---                                                                                                                                  | ---                                                                                                                                                                                                                                                    |
| [Contents.json](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner/Assets.xcassets/AppIcon.appiconset/Contents.json) | Optimizing Icon Design achieves seamless user experience on macOS by providing multiple icon sizes, ensuring smooth scaling across various devices and screen resolutions, thereby enhancing visual appeal and overall performance of the application. |

</details>

<details closed><summary>macos.Runner.xcworkspace.xcshareddata</summary>

| File                                                                                                                                             | Summary                                                                                                                                                                                                                                 |
| ---                                                                                                                                              | ---                                                                                                                                                                                                                                     |
| [IDEWorkspaceChecks.plist](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner.xcworkspace/xcshareddata/IDEWorkspaceChecks.plist) | Warns of IDERunner computation warning on macOS devices, indicating potential 32-bit application usage issues, prompting users to take necessary measures to ensure compatibility and optimize performance for their Quran-riwayat app. |

</details>

<details closed><summary>macos.Runner.xcodeproj.xcshareddata.xcschemes</summary>

| File                                                                                                                                   | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ---                                                                                                                                    | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| [Runner.xcscheme](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner.xcodeproj/xcshareddata/xcschemes/Runner.xcscheme) | Define Build ConfigurationBuild configurations are defined to allow for flexible building and testing options within a single scheme. Configure Debugging OptionsDebugging options, including the selected debugger identifier and launch style, can be configured for both launching and debugging processes.Establish Test ActionsTest actions, including test configuration and macros, are established to ensure proper testing of builds within the scheme. |

</details>

<details closed><summary>macos.Runner.xcodeproj.project.xcworkspace.xcshareddata</summary>

| File                                                                                                                                                               | Summary                                                                                                                                                                                                                            |
| ---                                                                                                                                                                | ---                                                                                                                                                                                                                                |
| [IDEWorkspaceChecks.plist](https://github.com/a-touman/quran-riwayat/blob/master/macos/Runner.xcodeproj/project.xcworkspace/xcshareddata/IDEWorkspaceChecks.plist) | Validation checks ensure platform compatibilityConfigures macOS Runner project settings for proper functionality Avoids 32-bit warning for Macintosh architecturesEnsures IDE Workspace checks are computed and warnings are shown |

</details>

<details closed><summary>linux.flutter</summary>

| File                                                                                                                                 | Summary                                                                                                                                                                                                                                                                                                                                                                       |
| ---                                                                                                                                  | ---                                                                                                                                                                                                                                                                                                                                                                           |
| [generated_plugin_registrant.cc](https://github.com/a-touman/quran-riwayat/blob/master/linux/flutter/generated_plugin_registrant.cc) | Registers plugins for Flutter application. Registers plugins for Flutter application by providing necessary registrations required to integrate third-party plugins within the application on Linux-based systems. This facilitates seamless plugin functionality and overall application stability. Essential for integrating various features in a comprehensive framework. |
| [generated_plugin_registrant.h](https://github.com/a-touman/quran-riwayat/blob/master/linux/flutter/generated_plugin_registrant.h)   | Generate Code for Flutter Plugins enables cross-platform plugin registration on Linux systems, allowing developers to easily integrate native plugins into their Flutter applications. This file is essential for integrating system-specific features and capabilities, making it an integral part of the overall architecture.                                              |
| [generated_plugins.cmake](https://github.com/a-touman/quran-riwayat/blob/master/linux/flutter/generated_plugins.cmake)               | Configure builds for Linux target by adding bundled libraries from generated plugins. The process involves listing plugin and FFI plugin dependencies, adding subdirectories for each plugin, and linking libraries to the binary name. This setup enables seamless plugin integration into the application build.                                                            |
| [CMakeLists.txt](https://github.com/a-touman/quran-riwayat/blob/master/linux/flutter/CMakeLists.txt)                                 | Configure builds for Linux by providing configuration provided via Flutter tool. Set up system-level dependencies using PkgConfig and check modules GTK, GLIB, and GIO. Create AOT library and set up headers for flutter Linux. Manage custom commands to assemble flutter tools backend.                                                                                    |

</details>

<details closed><summary>web.splash</summary>

| File                                                                                    | Summary                                                                                                                                                                                                                                                                                                                   |
| ---                                                                                     | ---                                                                                                                                                                                                                                                                                                                       |
| [splash.js](https://github.com/a-touman/quran-riwayat/blob/master/web/splash/splash.js) | Removing unnecessary splash elements on web platforms involves modifying browser attributes to eliminate visual distractions and improve user experience, resulting in a seamless interface that presents content without hindrance.                                                                                      |
| [style.css](https://github.com/a-touman/quran-riwayat/blob/master/web/splash/style.css) | Streamlining is achieved through styling elements in this file. Centering, containing, stretching, covering, and positioning are enabled via CSS classes, ensuring visually appealing and consistent presentation on the splash screen. Alignment is key, making sure text and images appear where theyre supposed to be. |

</details>

<details closed><summary>lib.translations</summary>

| File                                                                                                        | Summary                                                                                                                                                                                                                                                                                                                                                            |
| ---                                                                                                         | ---                                                                                                                                                                                                                                                                                                                                                                |
| [ar.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/translations/ar.dart)                   | Provides translations for key phrases in the Quran-riwayat apps interface, including buttons and error messages, making it easier to understand and use the app for users who prefer Arabic. Facilitates user experience by presenting a familiar language and navigation structure, catering to users expectations and comfort with native words and terminology. |
| [en.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/translations/en.dart)                   | Localizes user interface elements for the apps English translation. Provides text strings for various features, including navigation menus, book browsing, search functionality, and error messages, enabling a cohesive and intuitive user experience across different app versions and platforms.                                                                |
| [tr.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/translations/tr.dart)                   | Translating UI Elements**Provides translations for various UI elements, such as text labels and button descriptions, allowing users to interact with the app in their preferred language. This translation file contributes to the repositorys goal of making Quran-related content more accessible worldwide.                                                     |
| [translation.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/translations/translation.dart) | Enable multilingual support for the app by loading translations from external files (ar.dart, en.dart, tr.dart) and providing them through a single API in lib/translations/translation.dart. This implementation aligns with the larger repository architecture focusing on supporting different languages.                                                       |

</details>

<details closed><summary>lib.routes</summary>

| File                                                                                                | Summary                                                                                                                                                                                                                                                                                                                                     |
| ---                                                                                                 | ---                                                                                                                                                                                                                                                                                                                                         |
| [app_pages.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/routes/app_pages.dart)   | Define routes for navigation within the application. The AppPages class manages the routing configuration by listing pages to be navigated. It sets the initial route and defines a list of GetPage objects, each specifying a page name, and a corresponding view page.                                                                    |
| [app_routes.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/routes/app_routes.dart) | Defines routing configuration for the apps navigation flows. Establishes consistent URL paths throughout the application. Provides a standardized structure for app routes, enabling efficient navigation and seamlessness across different sections of the app. Simplifies route management with reusable constants and static references. |

</details>

<details closed><summary>lib.app.widgets</summary>

| File                                                                                               | Summary                                                                                                                                                                                                                                                                                                  |
| ---                                                                                                | ---                                                                                                                                                                                                                                                                                                      |
| [widgets.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/widgets/widgets.dart) | Modifying widgets on-demand is achieved through the lib/app/widgets/widgets.dart file. Customizable bottom sheets and tiles are provided to users via responsive design elements, ensuring seamless transitions across various screen sizes. Visual hierarchy and consistency are maintained throughout. |

</details>

<details closed><summary>lib.app.utilities</summary>

| File                                                                                                         | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ---                                                                                                          | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| [text_themes.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/utilities/text_themes.dart) | Configure text themes for the application defines styles for various typography elements, providing a cohesive visual identity. Styles are carefully designed to reflect the apps design language, leveraging screenutil and font weights from Roboto and Amiri fonts libraries. This setup ensures consistent styling across the app.                                                                                                                                                                                  |
| [app_colors.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/utilities/app_colors.dart)   | Define Color Palette**The `app_colors.dart` file establishes the color scheme for the application, providing a set of constants to ensure visual consistency across the project. These colors are carefully curated and aligned with the parent repositorys architecture.                                                                                                                                                                                                                                               |
| [constants.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/utilities/constants.dart)     | Define Constants establishes app identity through Quran Riwayat' branding and visual identity with a light theme featuring green accents, ensuring consistent styling throughout the application.Establishes a consistent user interface experience by defining colors for the app's light theme, incorporating green hues to provide visual clarity and emphasize key interactions. Defining these constants ensures that the Quran Riwayat app maintains a cohesive look and feel across all features and interfaces. |
| [variables.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/utilities/variables.dart)     | Storebook App Variables** Defines essential application variables for Quran Riwayat, enabling storage of last page viewed and current book ID, thus facilitating navigation across various routes within the app. These shared values support seamless transition between screens and pages.                                                                                                                                                                                                                            |
| [utilities.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/utilities/utilities.dart)     | Provides modal bottom sheets with custom shape and scroll control through a reusable popUpBottomMenu function that integrates seamlessly into the apps architecture.Handles local storage operations via the StorageUtility class, ensuring secure and efficient key-value pair management within the app.Displays customizable toast messages using the Toast utility class.                                                                                                                                           |

</details>

<details closed><summary>lib.app.pages.surah_list.model</summary>

| File                                                                                                                      | Summary                                                                                                                                                                                                                                                                                       |
| ---                                                                                                                       | ---                                                                                                                                                                                                                                                                                           |
| [surah_model.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/surah_list/model/surah_model.dart) | Serialization handles conversion between Surah objects and JSON data. It provides methods to convert lists of Surahs from JSON strings and back, making it easy to work with the models data. This functionality is critical for interacting with external APIs or storing data persistently. |

</details>

<details closed><summary>lib.app.pages.surah_list.controller</summary>

| File                                                                                                                                               | Summary                                                                                                                                                                                                                                                                                                                                                                   |
| ---                                                                                                                                                | ---                                                                                                                                                                                                                                                                                                                                                                       |
| [surah_list_controller.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/surah_list/controller/surah_list_controller.dart) | Enhances Quran Surah listing experience by fetching and displaying all Surahs from a JSON asset file. Dynamically updates displayed list based on search input and provides navigation to Reader page when a Surah is clicked. Stores selected book ID and last viewed page for later reference.Achieves: Surah data display, Dynamic filtering, Navigation, Data storage |

</details>

<details closed><summary>lib.app.pages.surah_list.view</summary>

| File                                                                                                                             | Summary                                                                                                                                                                |
| ---                                                                                                                              | ---                                                                                                                                                                    |
| [surah_list_view.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/surah_list/view/surah_list_view.dart) | Displaying individual Quranic Surah cards on a screen, handling searches and errors within the app.This widget can be integrated into various UI components as needed. |

</details>

<details closed><summary>lib.app.pages.reader.widgets</summary>

| File                                                                                                            | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ---                                                                                                             | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [widgets.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/reader/widgets/widgets.dart) | Implementing Search FunctionalityThe SearchForPageWidget serves as a custom widget for searching page numbers within the application. It consists of a text input field with filtering capabilities and an Go to Page button, facilitating users' navigation through specific pages.Navigating Specific PagesThis widget streamlines user experience by providing a simple interface for page number search. By minimizing cognitive load and leveraging intuitive design elements, it enables efficient navigation throughout the application. |

</details>

<details closed><summary>lib.app.pages.reader.controller</summary>

| File                                                                                                                                   | Summary                                                                                                                                                                                                                                                                    |
| ---                                                                                                                                    | ---                                                                                                                                                                                                                                                                        |
| [reader_controller.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/reader/controller/reader_controller.dart) | Activates navigation through a Quran document by enabling a Go To Page button. When clicked, it displays a bottom-up search bar to enter page numbers. On successful input, it animates the reader view to jump to the specified page and updates storage with every flip. |

</details>

<details closed><summary>lib.app.pages.reader.view</summary>

| File                                                                                                                 | Summary                                                                                                                                                                                                                                                                                                                     |
| ---                                                                                                                  | ---                                                                                                                                                                                                                                                                                                                         |
| [reader_view.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/reader/view/reader_view.dart) | Navigates users through the Quran, utilizing the PdfView widget to render pages from a PDF document. This implementation provides a clean interface for navigating pages, searching, and reacting to page changes, all while respecting RTL text direction. Enhances readability and engagement with the scripture content. |

</details>

<details closed><summary>lib.app.pages.home.model</summary>

| File                                                                                                              | Summary                                                                                          |
| ---                                                                                                               | ---                                                                                              |
| [book_model.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/home/model/book_model.dart) | Id, arabicName, and englishName, providing an essential foundation for subsequent functionality. |

</details>

<details closed><summary>lib.app.pages.home.controller</summary>

| File                                                                                                                             | Summary                                                                                                                                                                                                                                                                                                 |
| ---                                                                                                                              | ---                                                                                                                                                                                                                                                                                                     |
| [home_controller.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/home/controller/home_controller.dart) | Manages Quranic recitation routes for users by controlling navigation between various options presented to them on the applications home page.Provides data to display lists of quranic reading methods with details about each variation.Includes logic to maintain and update user interaction state. |

</details>

<details closed><summary>lib.app.pages.home.view</summary>

| File                                                                                                           | Summary                                                                                                                                                                                                                         |
| ---                                                                                                            | ---                                                                                                                                                                                                                             |
| [home_view.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/home/view/home_view.dart) | Rendering Home View achieves displaying Quran Books Grid with image, name, and detailed information through GridView.builder widget and navigating user to Surah page based on selection. It uses HomeController for book data. |

</details>

<details closed><summary>lib.app.pages.launch.widgets</summary>

| File                                                                                                                              | Summary                                                                                                                                                                                                                       |
| ---                                                                                                                               | ---                                                                                                                                                                                                                           |
| [languages_widget.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/launch/widgets/languages_widget.dart) | The code enables dynamic language selection in a multilingual application. It returns a list of RadioListTiles for various languages, each containing its respective translation key and displaying the chosen language name. |

</details>

<details closed><summary>lib.app.pages.launch.controller</summary>

| File                                                                                                                                   | Summary                                                                                                                                                                                                                                                                          |
| ---                                                                                                                                    | ---                                                                                                                                                                                                                                                                              |
| [launch_controller.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/launch/controller/launch_controller.dart) | Launches the apps core functionality by handling user interactions, such as language selection and navigation between features like the reader view and languages menu. Utilizes GetX controller for state management and stores essential data locally using storage utilities. |

</details>

<details closed><summary>lib.app.pages.launch.view</summary>

| File                                                                                                                 | Summary                                                                                                                                                                                                                                           |
| ---                                                                                                                  | ---                                                                                                                                                                                                                                               |
| [launch_view.dart](https://github.com/a-touman/quran-riwayat/blob/master/lib/app/pages/launch/view/launch_view.dart) | Launches a visually appealing splash screen showcasing the Quran Riwayat apps logo and main functionality, providing users with an overview of the apps features and inviting them to explore its content through customizable buttons and links. |

</details>

<details closed><summary>android.app</summary>

| File                                                                                           | Summary                                                                                                                                                 |
| ---                                                                                            | ---                                                                                                                                                     |
| [build.gradle](https://github.com/a-touman/quran-riwayat/blob/master/android/app/build.gradle) | This summary is limited to a maximum of 50 words as per your request. If youd like me to elaborate further or provide more context, please let me know! |

</details>

<details closed><summary>android.app.src.main.kotlin.com.example.quran_riwayat</summary>

| File                                                                                                                                           | Summary                                                                                                                                                                                                                                                                                                                                                                                                       |
| ---                                                                                                                                            | ---                                                                                                                                                                                                                                                                                                                                                                                                           |
| [MainActivity.kt](https://github.com/a-touman/quran-riwayat/blob/master/android/app/src/main/kotlin/com/example/quran_riwayat/MainActivity.kt) | Initializing Quran Riwayat on Android Launches Flutter Activity---------------------------Initiates the applications main activity, utilizing FlutterActivity to handle navigation and user interactions within the android app. Provides a seamless integration point between native Android features and cross-platform functionality. Employs standard development best practices throughout the codebase. |

</details>

<details closed><summary>windows.runner</summary>

| File                                                                                                            | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ---                                                                                                             | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| [runner.exe.manifest](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/runner.exe.manifest) | Enhances Windows application compatibility by specifying supported operating systems. Defines DPI awareness for high-resolution displays and lists supported OS IDs for Windows 7, 8, 8.1, and 10/11, ensuring seamless execution across different platforms.                                                                                                                                                                                                                                    |
| [flutter_window.cpp](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/flutter_window.cpp)   | Create native window on Windows platform, handling Flutter apps lifecycle events through Win32Window base class and registering plugins with Dart engine for Flutter app integration.Update system fonts by reloading them when the WM_FONTCHANGE message is received to keep font consistency across the app's UI elements. This enables seamless rendering of visual content in compliance with the Quranic texts displayed throughout the application, providing an engaging user experience. |
| [flutter_window.h](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/flutter_window.h)       | Hosting Flutter views across multiple platforms requires robust windowing system integration. The provided header file encapsulates a Flutter-enabled window implementation for the Windows platform. It integrates with Win32 to host a Dart-based view, facilitating cross-language compatibility.                                                                                                                                                                                             |
| [win32_window.h](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/win32_window.h)           | Provides a platform-agnostic abstraction for Win32 windows, enabling high DPI-aware rendering and input handling.Achieves robust window creation and management with built-in support for scaling, theme updates, and callback-based messaging. Integrates seamlessly with underlying system APIs, ensuring compatibility across different operating systems and display configurations.                                                                                                         |
| [main.cpp](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/main.cpp)                       | Launches a Flutter window on Windows platform. Initializes COM, attaches console when running from flutter run, and handles command line arguments. Creates and displays the Quran Riwayat application window with a size of 1280x720 pixels, enabling quit-on-close functionality.                                                                                                                                                                                                              |
| [utils.h](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/utils.h)                         | Create console instances for runner and Flutter library, redirecting output streams accordingly. Utility functions process UTF-16 encoded wide strings to UTF-8 encoded standard strings and retrieve command line arguments as vectors, enabling cross-platform consistency.Process command line arguments efficiently, converting UTF-16 strings to UTF-8 strings across different platforms. The resulting code enhances overall functionality and user experience.                           |
| [resource.h](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/resource.h)                   | Define Application IconsEstablishes icon identifiers for the Windows application, facilitating consistent visual branding throughout the user experience. The defined icons enable seamless integration with the operating systems visual language and contribute to a polished overall design.                                                                                                                                                                                                  |
| [utils.cpp](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/utils.cpp)                     | AttachConsole Creates a console instance for debugging purposes within Windows.GetCommandLineArguments Converts UTF-16 command line arguments into UTF-8 strings compatible with the Flutter Engine for proper execution.Utf8FromUtf16 Converts individual UTF-16 strings to their equivalent UTF-8 formats.                                                                                                                                                                                     |
| [win32_window.cpp](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/win32_window.cpp)       | Design a registry-based system for Win32 Window Class registration, allowing multiple instances of windows with distinct themes. This system ensures efficient management of registered window classes, facilitating seamless integration with existing applications and frameworks.                                                                                                                                                                                                             |
| [Runner.rc](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/Runner.rc)                     | Configures version information for Windows application.Generates icon resources based on Flutter version, including a text resource with a link to winres.h file, an icon with the lowest ID value (IDR_APP_ICON) referencing a custom app icon. Provides English language support for United States and includes necessary block variables for a successful build.                                                                                                                              |
| [CMakeLists.txt](https://github.com/a-touman/quran-riwayat/blob/master/windows/runner/CMakeLists.txt)           | Builds Windows applications by configuring CMake for Flutter projects. Establishes executable targets, compiles source files, defines build settings, and integrates dependencies. Utilizes standard settings and includes definitions for Flutter version and macro disabling for cross-platform compatibility. Ensures seamless assembly through CMake.                                                                                                                                        |

</details>

<details closed><summary>windows.flutter</summary>

| File                                                                                                                                   | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ---                                                                                                                                    | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| [generated_plugin_registrant.cc](https://github.com/a-touman/quran-riwayat/blob/master/windows/flutter/generated_plugin_registrant.cc) | Registers plugins for the PdfxPlugin feature across all platforms, ensuring seamless integration into the projects architecture.RegistersPdfxPlugin is responsible for integrating the plugin's functionalities into the application framework, guaranteeing proper function across various operating systems.Provides crucial functionality that enables the application to utilize the capabilities provided by the PdfxPlugin on different platforms. |
| [generated_plugin_registrant.h](https://github.com/a-touman/quran-riwayat/blob/master/windows/flutter/generated_plugin_registrant.h)   | Registering plugins is the primary function of this generated header file. It facilitates plugin registration for various Flutter platforms, enabling seamless integration with the Quran Riwayat application across different environments. The code provides a standardized interface for registering Flutter plugins.                                                                                                                                 |
| [generated_plugins.cmake](https://github.com/a-touman/quran-riwayat/blob/master/windows/flutter/generated_plugins.cmake)               | Configures plugins for Flutter applications on Windows.Registers the pdfx" plugin, adds dependencies to the build process, and links libraries to ensure correct functionality.                                                                                                                                                                                                                                                                          |
| [CMakeLists.txt](https://github.com/a-touman/quran-riwayat/blob/master/windows/flutter/CMakeLists.txt)                                 | Configure Flutter-level build steps, integrating ephemeral directories, wrapper roots, and plugin sources with dependencies. Establishing libraries for flutter, wrapper plugin, and app, linking them with required binaries and source files. Defining build settings, targets, and tool backend custom commands for windows.                                                                                                                          |

</details>

---

## 🚀 Getting Started

**System Requirements:**

* **Dart**: `version x.y.z`

### ⚙️ Installation

<h4>From <code>source</code></h4>

> 1. Clone the quran-riwayat repository:
>
> ```console
> $ git clone https://github.com/a-touman/quran-riwayat
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd quran-riwayat
> ```
>
> 3. Install the dependencies:
> ```console
> $ pub get
> ```

### 🤖 Usage

<h4>From <code>source</code></h4>

> Run quran-riwayat using the command below:
> ```console
> $ flutter run
> ```

### 🧪 Tests

> Run the test suite using the command below:
> ```console
> $ dart test
> ```

---

## 🛠 Project Roadmap

- [X] `► INSERT-TASK-1`
- [ ] `► INSERT-TASK-2`
- [ ] `► ...`

---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/a-touman/quran-riwayat/issues)**: Submit bugs found or log feature requests for the `quran-riwayat` project.
- **[Submit Pull Requests](https://github.com/a-touman/quran-riwayat/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/a-touman/quran-riwayat/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/a-touman/quran-riwayat
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://github.com{/a-touman/quran-riwayat/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=a-touman/quran-riwayat">
   </a>
</p>
</details>

---

## 🎗 License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## 🔗 Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-overview)

---
