## Reset VeriStand as Startup Workspace Tool ##

This workspace tool automates the process of resetting the VeriStand RT EXE as startup on a Real-Time target after connecting to that target from a LabVIEW project. This replaces the need to "re-install" the VeriStand engine from MAX or manually change and replace the .ini or .conf file.

### LabVIEW Version ###

Source code is in LabVIEW 2014

### Built Availability ###

Builds are not included. Download the source and build the build specification.

### Quality, Limitations ###

This IP is new but fairly simple. It has not undergone thorough testing.

Supports all NI Real-Time operating systems except VxWorks. It will "skip" any Windows targets it sees in the active system definition.

### Dependencies ###

NI LabVIEW, NI VeriStand. Requires WebDAV Server to be installed on target.

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*