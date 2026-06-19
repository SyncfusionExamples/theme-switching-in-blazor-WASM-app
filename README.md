# Theme Switching in Blazor WASM App

This repository contains a sample Blazor WebAssembly application demonstrating how to switch themes dynamically in a .NET 10 Blazor app using a shared layout, a Syncfusion theme selector, and runtime stylesheet updates.

## Features

- **Dynamic Theme Switching**: Updates the active Blazor theme without reloading the app
- **Built-in Theme Selection**: Provides a DropDownList with light, dark, and high-contrast theme options
- **Shared Layout Experience**: Keeps the theme switcher available across all pages
- **Runtime Style Loading**: Uses a JavaScript helper to swap the theme stylesheet on demand
- **Blazor Routing and Interactivity**: Includes sample pages for navigation and basic component behavior

## Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/en-us/download/dotnet)
- [Visual Studio Code](https://code.visualstudio.com/) with the [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) extension
- A supported browser such as Microsoft Edge, Google Chrome, Firefox, or Safari

## Run the sample in Visual Studio Code

1. Open the project folder in Visual Studio Code.
2. Install the recommended extensions if prompted.
3. Open the integrated terminal (`Ctrl + ~`).
4. Restore NuGet packages:

   ```bash
   dotnet restore
   ```

5. Build the project:

   ```bash
   dotnet build
   ```

6. Run the application:

   ```bash
   dotnet run
   ```

7. Open the URL shown in the terminal. The local port may vary depending on your environment and launch profile.

## References

- [Apply Blazor Themes and Switch Dynamically](https://blazor.syncfusion.com/documentation/appearance/themes)
- [Theme Studio for Blazor components](https://blazor.syncfusion.com/documentation/appearance/theme-studio)