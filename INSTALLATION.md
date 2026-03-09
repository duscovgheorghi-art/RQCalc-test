# Installation Guide for RQCalc Test

## Prerequisites
Before you begin installation, ensure you have the following prerequisites:
- **Windows Operating System**: Windows 10 or later.
- **.NET Framework**: Version 6.0 or later.
- **Visual Studio**: (optional for development)
  - Visual Studio 2022 or later with .NET desktop development workload.

## Installation Steps
1. **Download the Application**:
   - Go to the [releases page](https://github.com/duscovgheorghi-art/RQCalc-test/releases) of the RQCalc Test repository.
   - Download the latest release package.

2. **Unzip the Package**:
   - Locate the downloaded ZIP file and extract it to your desired location.

3. **Install Dependencies**:
   - Open a command prompt and navigate to the extracted folder.
   - Run the following command to install any required NuGet packages (if applicable):
     ```sh
     dotnet restore
     ```

4. **Build the Application**:
   - Still in the command prompt, use the following command:
     ```sh
     dotnet build
     ```
   - Ensure the build completes without errors.

5. **Run the Application**:
   - Execute the application using the following command:
     ```sh
     dotnet run
     ```

## Configuration
- Edit the `appsettings.json` file to customize your application settings.
- Common configurations include connection strings, logging levels, and external service API keys.

## Troubleshooting
- **Application does not start**:
  - Ensure all prerequisites are installed correctly.
  - Check the console output for any error messages and resolve them as indicated.

- **Dependency Issues**:
  - Make sure that all required packages are installed via `dotnet restore`.

- **Configuration Errors**:
  - Double-check the `appsettings.json` for errors in formatting or invalid settings.

## Updating Instructions
1. **Check for Updates**:
   - Regularly check the releases page for new versions.

2. **Download the Latest Version**:
   - Follow the same steps as in Installation Steps to download and install the new version.

3. **Migrate Configurations**:
   - If you have customized settings, ensure to update your `appsettings.json` with any new settings introduced in the current release.

## Notes
- Always back up your existing configurations and data before performing updates.
- For additional support, you can open an issue in the [repository](https://github.com/duscovgheorghi-art/RQCalc-test/issues).