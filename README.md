# Implementing Virtual Scrolling in the Blazor Scheduler

This quick start project demonstrates how to implement virtual scrolling in the [Blazor Scheduler](https://www.syncfusion.com/scheduler-sdk/blazor-scheduler) to efficiently handle large datasets. It showcases rendering only visible appointments within the viewport to improve performance and responsiveness, serving as a practical guide for building scalable scheduling applications using Syncfusion Blazor components.

## Features

- **Virtual Scrolling Support**: Efficiently handles large datasets without performance degradation
- **Smooth Performance**: Render only visible appointments for optimal memory usage
- **Blazor Integration**: Built with Syncfusion Blazor components
- **Responsive Design**: Works seamlessly across different screen sizes

## Prerequisites

- Visual Studio 2026 or Visual Studio Code
- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)

## How to run the project

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`Scheduler_Virtual_Wasm.csproj` or `Schedulers_Virtual_Server.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

For server,

```bash
cd Blazor-Scheduler-Virtual-Scrolling
cd Schedulers_Virtual_Server
dotnet restore
dotnet run
```

For WASM,

```bash
cd Blazor-Scheduler-Virtual-Scrolling
cd Scheduler_Virtual_Wasm
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Usage

This application demonstrates virtual scrolling implementation in the Blazor Scheduler. The virtual scrolling feature automatically activates when working with large appointment datasets, improving rendering performance.

## Documentation

- **Blazor Introduction**: https://blazor.syncfusion.com/documentation/introduction
- **Scheduler Getting Started**: https://help.syncfusion.com/scheduler-sdk/blazor/schedule/getting-started-with-server-app
- **Virtual Scrolling Guide**: https://help.syncfusion.com/scheduler-sdk/blazor/schedule/virtual-scrolling
- **License Registration**: https://blazor.syncfusion.com/documentation/getting-started/license-key/how-to-register-in-an-application

## Online Examples

- [Virtual Scrolling Demo](https://blazor.syncfusion.com/demos/scheduler/virtual-scrolling?theme=fluent2)

## Support

For questions or issues, please refer to the official Syncfusion documentation or contact Syncfusion support through their website.
