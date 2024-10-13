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


#### Project Structure
When you create a project using the KeyStone.Web template, the structure will look like this:

**wwwroot/**: Contains static files like CSS, JavaScript, and assets.

**Pages/**: Contains main page components such as Index.razor, Counter.razor, etc.

**Shared/**: Contains shared components and layouts used across the app.

**Program.cs**: Sets up services and configurations for the Blazor WebAssembly app.

**App.razor**: Defines the root component of the application.

