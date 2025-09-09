# BODAS-Studio v1.x

## What is BODAS-Studio?

???? Video for BODAS-Studio

BODAS-studio is a toolchain designed for developers to efficiently develop application software (ASW) for mobile machines. 
BODAS-studio currently includes the following tools:

|   | What is it?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | How to start |
|---|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| **Installer**  | Installs all necessary tools for using BODAS-Studio and checks for the correct installation of any required third-party tools such as Excel or 7-Zip.                                                                                                                                                                                                                                                                                                                                                                                                                                            |              |
| **ASWT (including BODAS Workflow)** | The ASW-Template (ASWT) provides a structured project base for development based on the MASAR architecture. It includes a predefined folder structure, a minimal application with basic functionalities (Error Manager, Parameter Manager, etc.), as well as scripts/tools for automating development tasks and serves as the foundation for every MASAR project. The ASWT includes a C Standard Library (MASAR-service library) that is safety-qualified and directly usable in safety projects, a pre-built BODAS Workflow and a toolbox for modeling MASAR components within MATLAB/Simulink. |              |
| **MASAR-studio** | Engineering tool for supporting the integration of components and functions in MASAR-based ASW. It provides workflows for managing classes, configuring parameters, and preparing diagnosis. All workflows also have a connection to the Service Interface tool to facilitate Service Interface creation.                                                                                                                                                                                                                                                                                        |              |
| **BODAS-service Editor** | BODAS-service Editor is a PC-Tool that enables the creation of user-defined content for BODAS-service. The tool is aimed towards software suppliers that want to provide the ability to use the BODAS-service tool for diagnosis of their ECU Software to their customers. By using this tool, software suppliers can determine which diagnostic services can be accessed from a specific application software in BODAS-service.                                                                                                                                                                 |              |
| **(Optional) BODAS-service** | BODAS-service is a PC-Tool used for servicing components of the Bosch Rexroth’s Mobile Electronics division. It supports all the necessary diagnostic functions for flashing, calibration and diagnostic of the electronic devices. Note that BODAS-service requires separate installation and licensing.                                                                                                                                                                                                                                                                                        |              |
|  **(Optional) MATLAB/Simulink** | MATLAB Simulink is a graphical programming environment for modeling, simulating, and analyzing multidomain dynamic systems. Currently used in BODAS-studio for modeling MASAR components and generating C-code, there are plans to extend its use to model entire systems without writing C-code. Updates on this expansion will be communicated promptly. Note that MATLAB Simulink requires separate installation and licensing.                                                                                                                                                               |              |

Each version of BODAS-studio comes with a migrator that assists developers in migrating their ASWT versions.
??? Where are the migrators???

## Where can I find information about the Toolchain?
[Community Link](https://community.mybodas.boschrexroth.com/t5/release-notes/bodas-studio/ta-p/2068)


## Use Shortcuts
<tabs>
    <tab title="Onboarding">
        <code-block lang="plain text">![Alt Text](new_topic_options.png){ width=450 }</code-block>
    </tab>
    <tab title="Getting Started">
        <code-block lang="xml">
            <![CDATA[<img src="new_topic_options.png" alt="Alt text" width="450px"/>]]></code-block>
    </tab>
</tabs>