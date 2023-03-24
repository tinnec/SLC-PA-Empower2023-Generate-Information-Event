
# Empower Workshop: PA Script Task

This script is a starting point for the workshop, designed to help you get up and running quickly. It includes the basic structure of a Process Automation (PA) script task that will be used throughout the workshop.

## Purpose

The purpose of this workshop is to create a PA script task for the 'Generate Information Event' activity.

The script will analyze and process profile parameters that are linked with DataMiner Object Model (DOM) fields that are in a named “process DOM instance”, using them to generate a DataMiner information event. By taking this approach, the script can offer a powerful way to customize automation workflows, allowing you to create highly tailored actions that meet your specific needs.

By the end of this workshop, you will have learned how to create your own PA script task, which you can use to interface with any DataMiner feature or object, providing a high degree of flexibility and customization.

## Prerequisites

Before you start the workshop, make sure you have the following installed on your computer:

-   [Git](https://git-scm.com/)
-   [Visual Studio](https://visualstudio.microsoft.com)
-   [DataMiner Integration Studio](https://community.dataminer.services/dataminer-integration-studio-other-downloads/)
-   [Empower - PA Prerequisites](https://catalog.dataminer.services/catalog/4125)

## Getting Started

To get started, follow these steps:

1.  Clone the repository to your local machine:
    
    ```bash
    git clone https://github.com/SkylineCommunications/SLC-PA-Empower2023-Generate-Information-Event.git
	```
    
2.  Open the automation script solution in Visual Studio and begin customizing it based on your needs.

## Usage

Once you have customized the script, you can test it by following these instructions::

1.  Publish the automation script XML file using the DataMiner Integration Studio editor available in Visual Studio.
2.  Create a basic Process Definition using the "Process Automation" app.
3.  Click 'Activate' to create an Activation Window.
4.  Push a token into the process using "Empower.PA.TestProcess" script.
5.  Verify the generated information event.

## Resources

Here are some resources that you may find helpful:

-   [Process Automation concepts](https://docs.dataminer.services/user-guide/Standard_Apps/PA/PA_Concepts.html)
-   [Creating script tasks](https://docs.dataminer.services/user-guide/Standard_Apps/PA/Getting_Started_with_PA/Creating_Activities/PA_Creating_script_tasks.html)
-   [DataMiner Community](https://community.dataminer.services/)