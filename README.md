# BAM_Inspector

BAM_Inspector is a C++ program designed for forensic analysis, focusing on the Background Activity Moderator (BAM) artifacts found in the Windows Registry. This tool provides a range of functionalities to assist in forensic investigations.

## Features

1. **Listing BAM Keys**: Enumerates BAM keys that have an execution date logged after the last logon time of the PC and lack a valid digital signature.
   
2. **Deleted Key Detection**: Checks for deleted BAM keys using different methods depending on the version of Windows. *There is a chance this may result in a false positive, so I would not consider it a bannable offense.*
   
3. **Deleted File Detection**: Verifies the existence of files associated with BAM keys.

## Usage

To use this tool, follow these steps:

1. Open Command Prompt as an administrator.
2. Enter the path to BAM_Inspector:
   ```sh
   C:\users\beegangw\downloads\BAM_Inspector



**Acknowledgements**
Special thanks to requiem for all his support on this tool!
