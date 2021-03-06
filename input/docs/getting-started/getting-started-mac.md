Title: Getting Started using Visual Studio for Mac
---
To get started using Axiom, using the Visual Studio Templates is the easiest method. Lets take a look at how to get a window open with Axiom rendering a blank screen in it.

## Prerequisites

Make sure the following dependencies have been installed prior to starting this tutorial

1. **One of the following editions of Visual Studio:**
    * [Visual Studio 2017 for Mac](https://visualstudio.microsoft.com/vs/mac/)

2. **OpenGL**
    * Mac uses OpenTK whch hosts OpenGl. You may or may not need this depending on your OS. Make sure you have the latest version installed.

## Get Started

1. **The Axiom Templates use NuGet to add the Axiom assemblies to the project. So you’ll need to install NuGet if you haven’t already, if you have skip to Step 2.**
    * Open VS2017 and then open the Extension Manager ( Tools-> Extensions Manager )
    * In the left hand pane select “Online Gallery”
    * In the Search Box, type “nuget”
    * Select the "NuGet Package Manager" item in the list
    * Click the “Download” button to install NuGet
2. **Install the Axiom Templates into Visual Studio 2017.**
    * If you haven’t done this step already, open VS2017 and then open the Extension Manager ( Tools-> Extensions Manager )
    * In the left hand pane select “Online Gallery”
    * In the Search Box, type “axiom”
    * Select the "Axiom Game Templates" item in the list
    * Click the “Download” button to install the templates
    ![Visual Studio Extension Manager](/assets/img/getting-started/VS2010_ExtensionManager.png)
3. **Once the Templates are installed, you can create a new Axiom Project**
    * File->New->Project
    * Select the Axiom category under Visual C#
    * Click the Axiom DirectX9 Game
    ![Visual Studio Extension Manager](/assets/img/getting-started/VS2010_NewProject.png)

4. **Enter your desired Project Name and Location and click ‘Ok’.**
5. **Wait while the project configures itself with the correct libraries, then hit F5 to compile and run**
        ![Visual Studio Extension Manager](/assets/img/getting-started/VS2010_RunProject.png)

6. **Once your satisfied with the neat blue screen, head on over to the [Basic Tutorial](/docs/tutorials) Updated! to continue learning how to build games with Axiom**
