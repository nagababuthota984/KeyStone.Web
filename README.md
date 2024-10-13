# KeyStone.Web Template

**KeyStone.Web** is a Blazor WebAssembly template designed to streamline the creation of Blazor WebAssembly applications.

## Getting Started with KeyStone.Web Template

### Prerequisites

Ensure that you have the following installed:

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Git](https://git-scm.com/) for cloning the repository

### Installation

#### Step 1: Clone the Repository

To install the **KeyStone.Web** template locally, first clone this repository:

```
git clone https://github.com/nagababuthota984/KeyStone.Web.git
```

```
cd KeyStone.Web
```
#### Step 2: Install the Template Locally

Once inside the project directory, install the template locally using the following command:

```
dotnet new install ./
```

#### Creating a New Project

Once the template is installed, you can create a new project based on the template with:

```
dotnet new keystone-webassembly -n YourProjectName
```
Replace **YourProjectName** with the name of your new project.

#### Uninstalling the Template

If you want to uninstall the template from your machine, you can do so by running:

```
dotnet new uninstall ./
```


## Project Structure

When you create a project using the **KeyStone.Web** template, the structure will look like this:

```
YourProjectName/
├── wwwroot/
├── Pages/
├── Shared/
├── Middlewares/
├── StateFactory/
├── Program.cs
└── App.razor
```
### Folder and File Overview

- **`wwwroot/`**:  
  This folder contains static files like CSS, JavaScript, and other assets required by the Blazor WebAssembly application.

- **`Pages/`**:  
  This folder holds the main page components of the Blazor app, such as:
  - **`Index.razor`**: The default landing page of the app.
  - **`Counter.razor`**: A sample page demonstrating simple Blazor features.
 
- **`Layout/`**:  
  The layouts used across the application are located in this folder.

- **`Shared/`**:  
  The shared components that are used across different parts of the application are located in this folder.

- **`Middlewares/`**:  
  This folder is used to manage custom middleware components for handling specific HTTP requests or other middleware pipeline functions in the Blazor WebAssembly app.
  It includes two files `AuthInterceptor` and `HttpClientResponseInterceptor` make sure to check these files are needed for your use case.

- **`StateFactory/`**:  
  This folder contains the classes or services responsible for managing the state of the application, such as authentication state management and local storage services.

- **`Program.cs`**:  
  This file sets up services, configurations, and entry points for the Blazor WebAssembly app. It initializes the WebAssembly host.

- **`App.razor`**:  
  This file defines the root component of the application. It manages routing and renders the page layout.

