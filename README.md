# How to import and export ICS files in Blazor Scheduler

This quick-start project demonstrates how to import and export calendar events in ICS (iCalendar) format using the [Blazor Scheduler](https://www.syncfusion.com/scheduler-sdk/blazor-scheduler). It showcases handling event data exchange across different platforms, enabling efficient integration and portability of calendar information while providing a practical guide for implementing standardized calendar management features in Blazor applications.

## Features

* Import calendar events from ICS files
* Export calendar events to ICS format
* Full calendar event management within Blazor Scheduler
* Support for recurring events in ICS format
* Easy integration with existing Blazor applications

## Prerequisites

- Visual Studio 2026 or Visual Studio Code
- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)

## How to run the project

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`Scheduler_Export_ICS.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

For server,

```bash
cd blazor-scheduler-import-export-ics
cd Scheduler_Server
dotnet restore
dotnet run
```

For WASM,

```bash
cd blazor-scheduler-import-export-ics
cd Scheduler_Wasm
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Documentation

For comprehensive information about implementing ICS import and export functionality in the Blazor Scheduler:

**Specific Feature Documentation**: https://help.syncfusion.com/scheduler-sdk/blazor/schedule/exporting#exporting-calendar-events-as-ics-file

**Online examples**: https://blazor.syncfusion.com/demos/scheduler/export-and-import-ics?theme=fluent2

**Framework Documentation Links:**

* **Blazor Introduction**: https://blazor.syncfusion.com/documentation/introduction
* **Schedule Component**: https://help.syncfusion.com/scheduler-sdk/blazor/schedule/getting-started-with-server-app

## Usage

After running the project, you can import ICS files and export your scheduler events. The application provides intuitive interfaces for both operations, allowing seamless integration of external calendar events and sharing of your schedule data in a standard format.

## Support

For more information and support, visit the Syncfusion Blazor documentation or check the online examples provided.