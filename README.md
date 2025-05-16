# KTU-PhD-Spring-School-on-Urban-Digital-Twins
Workshop:  Getting Started with Cesium and iTwin Platform

# Instructions

If you want to follow along with the code, you will need to install some application and packages.
## Required tools
We will be working with the iTwin Platform Developer pages at:
https://developer.bentley.com/my-itwins/
Check if you already have an account. It's not strictly necessary as I will be sharing the code required and can add you to any account as a member.

To synchronize model files, make sure you get the iTwin Synchronizer:
https://www.bentley.com/software/itwin-synchronizer/
and download the connector for the file format you want to work with.

#### Note:
In case you see an error message related to WMIC - Microsoft removed this from the latest Windows 11 update, please install WMIC manualy by opening the Start menu, type _optional features_ View features and add WMIC.

## My iTwins

Sample iModels for both, the Cesium viewer and the iTwin viewer can be accessed here

My iTwins | iTwin Platform https://developer.bentley.com/my-itwins/0673de9a-a480-4c57-afa1-9f2c107c536b/home/


## Cesium

Please create a free account at https://cesium.com/platform/cesium-ion/

## Getting Started with the iTwin Platform
### For the coding part

- [Node.js (LTS version)](https://nodejs.org/)

This tool provides the backend JavaScript runtime necessary for running and rendering code. It also allows you to run NPM commands.
Recommended tools

- [Google Chrome](https://www.google.com/chrome/)

The recommended browser for developing and debugging frontend JavaScript applications.

- [Visual Studio Code](https://code.visualstudio.com/)

Our recommended code editor and debugger for developing iTwin.js applications. It's free, open source, and includes a GUI for working with Git.

- [Git](https://git-scm.com/downloads)

Git is the version control system used to manage your code.

### Getting Started with the iTwin Platform

Guide and one-line install script

https://developer.bentley.com/tutorials/get-started-with-itwin-platform/

``npx create-react-app your-app-name --template @itwin/web-viewer --scripts-version @bentley/react-scripts``

can be pasted into the Visual Studio Code terminal with a right-click

_make sure to change the app name before running_

---------------
PhDSpringSchool2025
