# Overview
JFrog Visual studio extension adds JFrog Xray scanning of NuGet project dependencies to your Visual Studio.

# Building and Testing the Sources

To build the plugin sources, please follow these steps:
1. Clone the code from git.
2. Open Visual Studio.
3. Open Tools - Get Tools and Features
4. Select the workloads tab and scroll to the bottem for the Other Toolsets section. Install Visual Studio extension development. More information regarding the Visual Studio SDK can be found [here](https://docs.microsoft.com/en-us/visualstudio/extensibility/installing-the-visual-studio-sdk?view=vs-2017)
5. Once done re-open Visual Studio.
6. Click on *File* - *Open* - *Project/Solution* and navigate to the place you cloned this project and select the sln file.
7. To build the project, click on *Build* tab - *Build Solution*. The VSIX file will be placed in the **$PROJECT_LOCATION\bin\Release\JFrog.VSExtension.vsix**

# Developing the Plugin Code
If you'd like to help us develop and enhance the extension, this section is for you.
To build and run the plugin following your code changes, follow these steps:

1. From Visual Studio, open the extension project (please see above section number 6)
2. To lunch the extension: Click on *Debug* - *Start Debugging*.

# Code Contributions
We welcome community contribution through pull requests.
