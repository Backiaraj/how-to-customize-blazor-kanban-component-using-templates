# Customize the Blazor Kanban Component Using Templates

A small Blazor sample showing how to customize the [Blazor Kanban](https://www.syncfusion.com/gantt-sdk/blazor-kanban-board) component with templates for headers, swimlanes, and cards. Use the examples in this project to learn how to inject custom markup and data bindings into Kanban UI elements.

## Overview

This sample demonstrates three template types supported by the Blazor Kanban component:

- Header templates — customize column headers
- Card templates — customize card appearance and data fields
- Swimlane templates — customize swimlane row rendering

## Features

- Demonstrates `HeaderTemplate`, `CardTemplate`, and `SwimlaneTemplate` usage
- Examples of data-binding within templates
- Guidance on combining templates with drag/drop and board configuration

## Getting Started

### Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/how-to-customize-blazor-kanban-component-using-templates.git
cd how-to-customize-blazor-kanban-component-using-templates
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**:

- **Header Template**: https://help.syncfusion.com/gantt-sdk/blazor/kanban/columns#header-template
- **Card Template**: https://help.syncfusion.com/gantt-sdk/blazor/kanban/cards
- **Swimlane Template**: https://help.syncfusion.com/gantt-sdk/blazor/kanban/swimlane#template

**Online samples**: https://blazor.syncfusion.com/demos/kanban/header-template?theme=fluent2

## Troubleshooting & support

If you encounter issues, confirm that packages are restored, the project builds, and the license key is registered correctly. For more details about Syncfusion components consult the Syncfusion Blazor documentation.