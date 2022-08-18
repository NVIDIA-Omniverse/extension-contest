<!-- markdownlint-disable -->
<h1 align="center">
    NVIDIA Omniverse Developer Contest
    <br>
    #ExtendOmniverse | Closes September 9, 2022
</h1>
<h3 align="center">
    Extend the Omniverse and Win
</h3>
<p align="center">Welcome to our inaugural developer contest! The challenge is to create an extension in NVIDIA Omniverse. Use Omniverse Code and Omniverse Kit to build Python-based tools for 3D worlds. Start building an extension now for your chance to win an NVIDIA RTX GPU!
</p>

<p align="center">
     <a href="https://www.nvidia.com/extend-omniverse-contest/"><img src="images/ov-dev-contest-1920x1080.jpg"></a>
</p>

<p align="center">
We are looking for extensions that fall into one of the three categories:
</p>

<p align="center">
<strong>
Layout or scene authoring tools
    </strong>
</p>
<p align="center">
<strong>
Scene modifier or manipulator tools
    </strong>
</p>
<p align="center">
    <strong>
Use of Omni.ui
    </strong>
</p>

## Getting Started    
Ready to build your first extension? Check out the steps below to get up and running in no time. For additional details on prizes, eligibility, and requirements for the contest, visit the [official landing page](https://www.nvidia.com/en-us/omniverse/apps/code/developer-contest/) or the [announcement blog](https://developer.nvidia.com/blog/build-tools-for-the-3d-world-with-the-extend-the-omniverse-contest/). 

### Installation Prerequisites  
:heavy_check_mark: Install [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/download/)  
:heavy_check_mark: Install [Omniverse Code](https://developer.nvidia.com/nvidia-omniverse-platform/code-app)  
:heavy_check_mark: Install [Visual Studio Code](https://code.visualstudio.com/download)  

### Building Your First Extension  
Once the steps above are complete, getting started is easy. Simply launch Omniverse Code from the NVIDIA Omniverse Launcher, then navigate to the Extensions tab.  
![Extensions Window](images/extensions-window.jpg)

Click the green + icon in the top left corner to create an extension from the template.  
![New Extension](images/new-extension.jpg)

Choose the directory you'd like to create your extension, then provide a folder & project namespace to complete the project.  

![Project Name](images/project-name.jpg)
![Extension Name](images/extension-name.jpg)

Visual Studio Code should automatically open with your newly created project, and you're ready to begin developing your first extension! Navigate to `exts\[your.project.namespace]\your\project\namespace\extension.py` to review the placeholder code and observe the extension window that is now open in Omniverse Code.  
![VSCode Project](images/vscode-project.png)

You can also check out our [Spawn Primitives Extension Sample](https://github.com/NVIDIA-Omniverse/kit-extension-sample-spawn-prims) tutorial for getting up and running within 10 minutes.  

## Samples & Resources  
Below are a number of resources that will help accelerate your learning journey.

### Extension Samples  
Kit comes bundled with a number of extensions, which can be found inside `app/kit/exts`, `app/kit/extscore`, and `app/exts`. Most of these are in Python, and the source is available for your continued learning

**Layout & Scene Authoring Samples**  
* [Spawn Primitives Sample](https://github.com/NVIDIA-Omniverse/kit-extension-sample-spawn-prims) - Leverage the Command tab to spawn a set of primitives within your scene
* [Scatter Tool Sample](https://github.com/NVIDIA-Omniverse/kit-extension-sample-scatter) - Randomly distribute primitives within a given bounds
* [CSV Reader Sample](https://github.com/NVIDIA-Omniverse/kit-extension-sample-csv-reader) - Learn how to populate a scene using data from a CSV file
 
**Scene Modifier, Manipulator Tool Samples**  
* [Viewport Info & Manipulator Samples](https://github.com/NVIDIA-Omniverse/kit-extension-sample-ui-scene) - A collection of samples demonstrating how to render additional metadata and create custom manipluators within the Omniverse viewport
* [Viewport Reticle Sample](https://github.com/NVIDIA-Omniverse/kit-extension-sample-reticle) - Use `omni.scene.ui` to draw GUI reticles & compositions within the Omniverse viewport

**Styling Samples**  
* [UI Window Samples](https://github.com/NVIDIA-Omniverse/kit-extension-sample-ui-window) - A collection of samples demonstrating how to layout and style custom dialog windows using Omniverse Kit

### Technical Documentation  
* [Omniverse Code Overview](https://www.youtube.com/watch?v=j1Pwi1KRkhk) - The Omniverse Code app contains interactive documentation experimenting with key building blocks available in Kit
* [Python Kit API Reference & Technical Documentation](https://docs.omniverse.nvidia.com/py/kit/index.html)
* [NVIDIA Omniverse Resource Center - Extensions](https://developer.nvidia.com/nvidia-omniverse-developer-resource-center#extensions) - includes videos and additional resources for learning how to develop extensions

### Additional Resources  
We have a fantastic community of active developers in our forums and the official Omniverse Discord channel. See the links below for support and connecting with the broader Omniverse developer community:
* [Omniverse Extension Forums](https://forums.developer.nvidia.com/c/omniverse/extension/399)
* [NVIDIA Omniverse Discord](https://forums.developer.nvidia.com/t/omniverse-discord-server-is-live/178422)

## Submitting Your Extension  
Below is a high level checklist of what you'll need to do in order to submit your entry. You can also check out the [How to Submit](https://www.youtube.com/watch?v=z8khQyHT_44) video for detailed instructions on how to correctly publish your extension.
 
### Prepare    
:heavy_check_mark: Developer & test your extension  
:heavy_check_mark: Update your `extension.toml` config file found in `exts\[project]\config`  
:heavy_check_mark: Update your extension's `README.md` & `CHANGELOG.md` found in `exts\[project]\docs`  
:heavy_check_mark: Update your extension's icon.png & preview.png images found in `exts\[project]\data`  
### Publish  
:heavy_check_mark: Publish your project to a public repo on GitHub  
:heavy_check_mark: Add the `omniverse-kit-extension` [Topic](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics) to your repo so that it shows up [here](https://github.com/topics/omniverse-kit-extension)  
:heavy_check_mark: Publish a [Release](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository) for your project  
### Submit  
:heavy_check_mark: Create a short video demonstrating what your extension does  
:heavy_check_mark: Complete the submission form from the contest landing page [here](https://www.nvidia.com/en-us/omniverse/apps/code/developer-contest/)

