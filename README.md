# Theme Switching in Blazor WASM App

This sample demonstrates how to switch themes dynamically in a .NET 10 Blazor WebAssembly app using a shared layout, a Syncfusion theme selector, and runtime stylesheet updates.

## Overview

The sample includes:

- A shared layout (`MainLayout.razor`) with a theme selector
- Sample pages (`Home`, `Counter`, `Weather`)
- Theme assets loaded from `wwwroot/index.html`
- Application styles in `wwwroot/css`
- Static assets and sample data under `wwwroot`

## Features

- **Dynamic Theme Switching**: Updates the active Syncfusion theme without reloading the app
- **Built-in Theme Selection**: Provides a DropDownList with light, dark, and high-contrast theme options
- **Shared Layout Experience**: Keeps the theme switcher available across all pages
- **Runtime Style Loading**: Uses a JavaScript helper to swap the theme stylesheet on demand
- **Blazor Routing and Interactivity**: Includes sample pages for navigation and basic component behavior
- **Static Asset Support**: Loads CSS, scripts, icons, and sample data from `wwwroot`

## Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/en-us/download/dotnet)
- [Visual Studio Code](https://code.visualstudio.com/) with [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) extension
- A supported browser such as Microsoft Edge, Google Chrome, Firefox, or Safari

## Run the sample in Visual Studio Code

1. Open the project folder in Visual Studio Code.
2. Install the recommended extensions if prompted.
3. Open the integrated terminal.
4. Restore the NuGet packages:

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

7. Open the URL shown in the terminal. The local port may vary based on the launch profile and environment.

## References

- [Apply Blazor Themes and Switch Dynamically](https://blazor.syncfusion.com/documentation/appearance/themes)
- [Getting Started with Blazor Web App](https://blazor.syncfusion.com/documentation/getting-started/blazor-web-app)
- [Getting Started with Blazor WebAssembly Standalone App](https://blazor.syncfusion.com/documentation/getting-started/blazor-webassembly-app)