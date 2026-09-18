# Title

Customizing Rows of Blazor Data Grid Using Templates

## Overview

This sample demonstrates how to customize the appearance of records in the Syncfusion Blazor DataGrid by using a Row Template. Instead of displaying data using the default row rendering behavior, the DataGrid renders each row through a customized template that allows rich layouts, custom styling, images, and additional business information to be displayed within a single row. This approach is useful when creating card-like row presentations, employee directories, product catalogs, customer profiles, or other scenarios that require enhanced visual representation beyond standard tabular cells.

## Key Features

- Uses the Syncfusion Blazor DataGrid component to display structured data.
- Implements a custom `RowTemplate` to completely control how each data record is rendered.
- Demonstrates rendering multiple fields within a single customized row layout.
- Shows how images, text blocks, and additional record details can be displayed within the row template.
- Replaces the default DataGrid row appearance with a fully customized UI structure.
- Demonstrates template-driven rendering while preserving DataGrid functionality.
- Provides a practical example of building rich and visually appealing row layouts.
- Shows how business data can be organized and presented using custom HTML and CSS within the row template.
- Serves as a reference implementation for advanced row customization scenarios in Syncfusion Blazor DataGrid applications.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file `CustomGridRowSample.sln`.
3. Restore all NuGet packages.
4. Set the `Server` project as the startup project.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the Server project directory.

```bash
cd Server
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `Client/Pages/Index.razor` — contains the Syncfusion Blazor DataGrid implementation, custom RowTemplate definition, sample data binding configuration, and row rendering logic.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid Row Template documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/row-template

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.