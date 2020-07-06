# CTX-Blue-Prism
A set of subtasks that enables the integration with Blue Prism

The additional subtasks are:
## 1. Get-Log-BPGL
This subtask retrieves the Log of a Blue Prism Process. It does that by means of the session ID of that executed Process.
## 2. Get-Status-BPGS
Use this subtask gets the status of a Blue Prism Process. It does that by means of the session ID of that executed Process.
## 3. Run-Process-BPRP
Use this subtask to trigger a Blue Prism Process. You can do that by supplying the following variables:
##### Blue Prism user [required]
The Blue Prism user that is used to run the Process
##### Blue Prism user password [required]
The password of the Blue Prism user
##### Blue Prism Processname [required]
The name of the Blue Prism Process that needs to be started 
##### Process Start Parameters [optional]
Sometimes a Process requires input parameters. Use this variable as an XML to pass the variables
##### BP Machine [optional]
The machine that runs the Blue Prism software.
If not supplied the subtask considers that Blue Prism is running on the Cortex Server.
##### OS user [optional]
The Operating System Username that has the ability to run a Blue Prism process on the BP Machine.
If not supplied the subtask considers that Blue Prism is running on the Cortex Server.
##### OS password [optional]
The password of the Operating System Username that has the ability to run a Blue Prism process on the BP Machine.
If not supplied the subtask considers that Blue Prism is running on the Cortex Server.

## Note
These subtasks consider Blue Prism to be installed in it's default installation folder: _"C:\Program Files\Blue Prism Limited"_

# Installation Instructions
Download the Studio Package file and Import it into your Cortex Environment.
Don't forget to apply rights using the Studio Authorization module.

:thumbsup: Success! :wink:
