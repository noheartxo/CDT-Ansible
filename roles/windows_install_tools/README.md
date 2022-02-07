Deployment of tools such as Sysinternals and Wireshark exist here. Both are installed with the chocolatey Windows Package Manager. 

Wireshark installs without the npcap.exe which is needed in order to properly capture network traffic on Windows machines. Due to npcap not allowing for silent installation unless one has the OEM or Enterprise version of the executable, it is installed in C:\Temp\Ansible. Manual installation is required before of aforementioned issues. 

Sysinternals installs into the default chocolatey path: C:\ProgramData\chocolatey\lib\sysinternals. 