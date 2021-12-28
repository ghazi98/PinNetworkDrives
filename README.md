# PinNetworkDrives

# About
I created a basic PowerShell based script that pins Kitchen Cabinets and Stones network drive to a client's quick access tab with a single click which is easier than entering the FQDN or IP address to manually add it.

# Improvements or further implementation
Windows will throw an unhandled exception error if the script is trying to add a network drive that is not accessable on the network. I would like to handle unexpected errors using try ... catch ... which will check weather there is connectivity to the network drive, if not, warn the user and exit. If there is connectivity, proceed.

https://user-images.githubusercontent.com/61443806/147520096-b072e104-7084-473b-b868-7cee167326a1.mp4

