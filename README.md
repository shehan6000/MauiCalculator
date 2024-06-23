# .NET MAUI Calculator

A cross-platform calculator application built with .NET MAUI, allowing you to run the app on Android, iOS, macOS, and Windows with a single codebase.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division
- Clear entry
- Toggle between positive and negative
- Percentage calculation
- Decimal point entry

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) with .NET MAUI workload
- [.NET 6.0 SDK or later](https://dotnet.microsoft.com/download/dotnet/6.0)
- A Mac with Xcode for iOS development (if targeting iOS)

## Getting Started

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/maui-calculator.git
    cd maui-calculator
    ```

2. **Open the project:**

    Open the solution file (`.sln`) in Visual Studio 2022.

3. **Set the target platform:**

    In Visual Studio, select the target platform (Android, iOS, macOS, or Windows) from the dropdown menu at the top.

4. **Build and run the application:**

    Press `F5` or click the `Run` button to build and run the application on the selected platform.

## Project Structure

- `MauiProgram.cs`: Sets up the MAUI app and configures services and fonts.
- `MainApplication.cs`: Android-specific application setup.
- `MainPage.xaml`: Defines the UI of the main calculator page using XAML.
- `MainPage.xaml.cs`: Contains the code-behind logic for the main calculator page.
- `App.xaml`: Defines application-level resources.
- `App.xaml.cs`: Contains the code-behind for `App.xaml`.

## Building for Different Platforms

### Android

1. **Configure the Android project:**

    Ensure the `AndroidManifest.xml` file is correctly set up with the necessary permissions.

2. **Set the build configuration to Release:**

    In Visual Studio, set the build configuration to `Release`.

3. **Build the APK:**

    Right-click on the Android project in the Solution Explorer.
    Select **Publish** -> **Archive...**
    Once the build is complete, select the archived build and click **Distribute**.
    Follow the instructions to sign the APK and generate the final package.

### iOS

1. **Configure the iOS project:**

    Ensure the `Info.plist` file is correctly set up with the necessary settings.

2. **Set the build configuration to Release:**

    In Visual Studio, set the build configuration to `Release`.

3. **Build the IPA:**

    Right-click on the iOS project in the Solution Explorer.
    Select **Publish** -> **Archive...**
    Once the build is complete, select the archived build and click **Distribute**.
    Follow the instructions to sign the IPA and generate the final package.

### macOS

1. **Configure the macOS project:**

    Ensure the `Info.plist` file is correctly set up with the necessary settings.

2. **Set the build configuration to Release:**

    In Visual Studio, set the build configuration to `Release`.

3. **Build the App Bundle:**

    Right-click on the macOS project in the Solution Explorer.
    Select **Publish** -> **Archive...**
    Once the build is complete, select the archived build and click **Distribute**.
    Follow the instructions to sign the app and generate the final package.

### Windows

1. **Configure the Windows project:**

    Ensure the `Package.appxmanifest` file is correctly set up with the necessary settings.

2. **Set the build configuration to Release:**

    In Visual Studio, set the build configuration to `Release`.

3. **Build the MSIX Package:**

    Right-click on the Windows project in the Solution Explorer.
    Select **Publish** -> **Create App Packages...**
    Follow the instructions to create the MSIX package.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- .NET MAUI Documentation: [docs.microsoft.com/dotnet/maui](https://docs.microsoft.com/dotnet/maui)
- Visual Studio Documentation: [docs.microsoft.com/visualstudio](https://docs.microsoft.com/visualstudio)
