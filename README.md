# 🔍 kmp-api-lookup-mcp - Find Kotlin Apple API details fast

[![](https://img.shields.io/badge/Download-App-blue)](https://github.com/Heymonth/kmp-api-lookup-mcp)

## 📖 About this application

You use this tool to look up Apple framework information within Kotlin Multiplatform projects. This application acts as a helper server for your development environment. It changes how you search for symbols, classes, and methods when you work with Kotlin and iOS. 

The software builds a local index of your klib files. This approach makes your searches run without delay. You see compact cards for each symbol. You also inspect metadata when you need more detail. This tool supports your workflow by keeping the technical facts you need close by.

## 💻 System requirements

Your computer must meet these basic standards to run this software:

*   Operating System: Windows 10 or Windows 11.
*   Memory: 4GB of RAM or more.
*   Storage: 200MB of free space for the index files.
*   Internet Connection: Required for the initial download and rare updates.

## 🚀 Downloading the software

Follow these steps to obtain the files for your system:

1. Visit the project website at: https://github.com/Heymonth/kmp-api-lookup-mcp
2. Locate the Releases section on the right side of the page.
3. Choose the latest version available for Windows.
4. Select the file ending in .zip or .exe to start the transfer to your computer.

[![](https://img.shields.io/badge/Download-Release-grey)](https://github.com/Heymonth/kmp-api-lookup-mcp)

## ⚙️ Setting up the environment

The application requires a small amount of setup before you start. Follow these instructions in order:

1. Extract the contents of the download file to a folder you recognize. Choose a permanent location like your Documents folder.
2. Open your command prompt or terminal window.
3. Navigate to the folder you created in step 1.
4. Run the executable file by typing its name and pressing Enter.
5. Grant the application network permissions if your firewall asks for approval.

The tool monitors your chosen directories to build its index. It works in the background while you write code.

## 🛠️ Using the application

Once the server runs, it connects to your code editor. You trigger searches by typing the name of the function or class you want to find. The application returns a set of results immediately. 

*   Search: Type the name of a symbol into the input field.
*   View Cards: Results appear as small information cards. These cards show the signature and package location.
*   Inspect Metadata: Click on a card to see the full set of technical data for that symbol.

The index stays fresh by scanning your project folder for changes. You do not need to restart the server manually when you add new libraries to your project.

## 💡 Troubleshooting common issues

If you encounter problems, check these items:

*   Does the folder contain the index files? Check the application directory for a folder named index.
*   Is the port in use? If the application fails to start, another program might claim the network port. Restart your computer to resolve this conflict.
*   Are the files blocked? If Windows restricts the application, right-click the file, select Properties, and check the Unblock box if it exists.

## 📁 Project structure

This application keeps files organized for stability:

*   bin/: Contains the application execution files.
*   config/: Stores user settings and preferences.
*   data/: Holds the local klib index.
*   logs/: Provides text files that help diagnose performance issues.

## 📈 Performance tips

This application processes large amounts of data. Follow these tips to keep the speed high:

*   Limit the number of libraries scanned. You control the scan paths in the configuration file.
*   Keep the application in a folder on your primary drive. SSD storage improves the index lookup time significantly.
*   Clear the cache if search results feel outdated. Use the command line flag to refresh the index manually.

## 📝 Configuration options

Users adjust settings in the config folder. Open the file named settings.json in any text editor. You change specific behaviors like the port number or the refresh rate. Save the file and restart the application to apply the changes. 

Do not edit files inside the data folder. These files update automatically as the index grows or changes. Manual edits to these files cause errors in your search results.