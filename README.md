# BAM_Inspector

BAM_Inspector is a C++ program designed for forensic analysis, focusing on the Background Activity Moderator (BAM) artifacts found in the Windows Registry. This tool provides a range of functionalities to assist in forensic investigations.

## Features

1. **Listing BAM Keys**: Enumerates BAM keys that have an execution date logged after the last logon time of the PC and lack a valid digital signature.
   
2. **Deleted Key Detection**: Checks for deleted BAM keys using different methods depending on the version of Windows. [REMOVED UNTIL FALSES ARE FIXED]
   
3. **Deleted File Detection**: Verifies the existence of files associated with BAM keys.

## Usage

To use this tool, follow these steps:

1. Open Command Prompt as an administrator. 
2. You no longer need to manually download RawCopy.exe from the repo so simply enter the path to BAM_Inspector:
   ```sh
   C:\users\beegangw\downloads\BAM_Inspector

**Acknowledgements**
Special thanks to requiem for all his support on this tool!
