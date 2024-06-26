# BAM_Inspector

This repository contains a C++ program designed for forensic analysis, focusing on the Background Activity Moderator (BAM) artifacts found in the Windows Registry. The tool offers a range of functionalities, including:

1. Listing BAM Keys: It enumerates the BAM keys that have an execution date logged after the last logon time of the PC and lack a valid digital signature

2. Deleted Key Detection: A key feature of this tool is its ability to check for deleted BAM key (It will use a different method of checking for deleted keys dependent on the version of windows)

3. Deleted File Detection: The program will check for the existence of the file. 


Shoutout requiem for all his support on this tool! 




